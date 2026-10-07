<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: rorkai-app-store-connect-cli-skills-asc-notarization
description: "Step-by-step xcodebuild + asc workflow to Developer ID-sign and Apple-notarize macOS apps, zips..."
---

# macOS notarization with asc — archive, export, submit, staple

Curated by Skill Harbor — @rorkai's step-by-step skill for notarizing macOS apps for distribution outside the App Store. The workflow runs: preflight (verify a Developer ID Application identity exists in the keychain, inspect trust settings read-only), archive with `xcodebuild`, export with Developer ID signing via an ExportOptions plist, verify the exported signature and timestamp chain strictly (never re-sign as a diagnostic step), create the notarization ZIP with `ditto`, submit with `asc notarization submit` (fire-and-forget or `--wait` with custom polling and upload timeouts), check status and fetch the developer log on failure, then staple the ticket (including DMG/PKG variants — PKG needs the separate Developer ID Installer certificate). Includes troubleshooting for the classic failures (invalid trust settings, unsigned nested binaries, missing hardened runtime, missing secure timestamp) and cautions against destructive "fixes" like removing trust overrides without authorization. MIT-licensed. Honest caveats: macOS-only and Xcode-dependent by nature; you need an Apple Developer Program membership and a Developer ID certificate in the local keychain — the API cannot create those, and signing identities live on your machine, not in the cloud; notarization submissions hit Apple's servers, so expect real waiting time. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/rorkai-app-store-connect-cli-skills-asc-notarization
- Fiche en français: https://theskillharbor.com/fr/products/rorkai-app-store-connect-cli-skills-asc-notarization
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/rorkai/app-store-connect-cli-skills/blob/main/skills/asc-notarization/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

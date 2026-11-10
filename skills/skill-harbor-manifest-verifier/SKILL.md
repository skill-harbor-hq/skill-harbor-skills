<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: skill-harbor-manifest-verifier
description: "Verify a Skill Harbor listing before you install it: fetch its signed manifest, recompute the..."
---

# Skill Harbor Manifest Verifier

The Skill Harbor Manifest Verifier checks a Skill Harbor listing before you install it, with facts instead of sales copy. It fetches the listing's signed manifest, recomputes the bundle hash from the per-file hashes, verifies the Ed25519 signature against Skill Harbor's public key, and can check one file hash against the pinned commit on GitHub. If you already installed a version, it compares the two manifests and tells you whether anything changed, because a yes for one version never covers an update.

The checks run in order and each one is reported honestly. The signature verifies the declared bundle hash, not the files, so a tampered file list is caught by the bundle-hash check, not by the signature check. Both must pass. A skipped check is never a pass: if no Ed25519 verifier is available, the signature check is skipped and the verdict is INCOMPLETE, not PASS. An unsigned listing is not verified and gets no badge, and a revoked or suspended listing means do not install, even if the hashes still match.

This skill is a verifier, not an installer. It never installs anything, never executes an install prompt, and never asks you to skip a check. Permissions in the manifest are declared, not exhaustive, and shown as information only. It works with manifest v1 today and with the MCP v2 consent package, which uses the same manifest format. Free to use under the Skill Harbor House License v1.0: you may install and use it for yourself, you may not resell it or pass it off as...

- Listing: https://theskillharbor.com/products/skill-harbor-manifest-verifier
- Fiche en français: https://theskillharbor.com/fr/products/skill-harbor-manifest-verifier
- Category: Security
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/house-skills/blob/main/skill-harbor-manifest-verifier/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

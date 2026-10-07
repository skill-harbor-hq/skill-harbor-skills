<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: caffeinelabs-extension-email-verification
description: "Verify email addresses with click-to-confirm links"
---

# Email: Verification

💳 Curated by Skill Harbor — the email verification extension for Caffeine AI apps: send a verification email whose `{{VERIFICATION_URL}}` link proves the recipient owns the address, with a registry module (`verifiedEmails`) tracking which addresses are confirmed. A mixin handles the verification callback automatically; you check status with `VerifiedEmails.contains` instead of tracking it yourself. Depends on `caffeinelabs-extension-email`. Requires a Caffeine AI Plus or Pro subscription — there is no free tier for this skill. Distinct from `caffeinelabs-extension-email` (general transactional mail): this is proof-of-ownership links only. By @caffeinelabs, listed here with credit to its creator. Honest caveats: works only inside a Caffeine AI build (Internet Computer canister + Motoko); the verification body must contain the `{{VERIFICATION_URL}}` placeholder or the link never renders. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/caffeinelabs-extension-email-verification
- Fiche en français: https://theskillharbor.com/fr/products/caffeinelabs-extension-email-verification
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/caffeinelabs/skills/blob/main/skills/extension-email-verification/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

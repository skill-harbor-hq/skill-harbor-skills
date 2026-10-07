<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: caffeinelabs-extension-email
description: "Send one-off service and transactional emails from a Caffeine AI backend"
---

# Email: Service/Transactional

💳 Curated by Skill Harbor — the service/transactional email extension for Caffeine AI apps: one call (`sendServiceEmail`) from the backend Motoko canister sends a single email per recipient — order confirmations, notifications, password resets. Uses the prefabricated `mo:caffeineai-email/emailClient.mo` module with typed results (`#ok` / `#err`), so failures surface as a clean error string instead of a crash. Requires a Caffeine AI Plus or Pro subscription — there is no free tier for this skill. Distinct from `caffeinelabs-extension-email-marketing` (subscriber topics and campaigns) and `caffeinelabs-extension-email-raw` (multi-recipient to/cc/bcc): this one is strictly one-off transactional mail, one individual email per recipient. By @caffeinelabs, listed here with credit to its creator. Honest caveats: works only inside a Caffeine AI build (Internet Computer canister + Motoko); don't use it for marketing or verification mail — sibling skills exist for those. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/caffeinelabs-extension-email
- Fiche en français: https://theskillharbor.com/fr/products/caffeinelabs-extension-email
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/caffeinelabs/skills/blob/main/skills/extension-email/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

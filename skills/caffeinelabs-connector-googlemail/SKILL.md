<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: caffeinelabs-connector-googlemail
description: "Send email as the signed-in user's own Gmail account via OAuth"
---

# Gmail Connector

Honest caveats: works only inside a Caffeine AI build; you must create a Google Cloud Web-application OAuth client, register the app's `/connect/gmail` callback URI as an authorized redirect, and enter the client ID/secret through the app's admin settings page (the secret stays in the canister, never the frontend); the skill explicitly forbids hand-rolled HTTP calls to Google endpoints — only the mops packages are the supported path. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/caffeinelabs-connector-googlemail
- Fiche en français: https://theskillharbor.com/fr/products/caffeinelabs-connector-googlemail
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/caffeinelabs/skills/blob/main/skills/connector-googlemail/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

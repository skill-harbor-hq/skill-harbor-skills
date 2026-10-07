<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: rorkai-app-store-connect-cli-skills-asc-subscription
description: "Bulk-create or update display names (and descriptions) for subscriptions, subscription groups and..."
---

# App Store Connect subscription localization: bulk-localize subscription, group and IAP names across locales

💳 **Paid API required** — App Store Connect API access requires a paid Apple Developer Program membership ($99/year). Curated by Skill Harbor — @rorkai's skill for bulk-localizing subscription, subscription-group and in-app-purchase display names across all App Store locales with the `asc` CLI, without the App Store Connect UI: choose the API scope first (API 4.4.1 version-scoped v2 resources only — the v1 product/group-scoped resources are deprecated and emit migration warnings), resolve or create `PREPARE_FOR_SUBMISSION` versions with the strict zero/one/many rule (zero matches → create, one → reuse, many → stop and require an explicit version ID), then list existing localizations first, create only missing locales, and update by resolved ID. Gotchas documented: version IDs differ from product/subscription/group IDs; live Apple service rejects empty descriptions and `--clear-description` for subscription/IAP-version localizations even though the schema permits JSON null — creating a missing locale requires a non-empty description, and display-name-only runs must skip missing locales until a description is provided; no bulk API exists, each locale needs a separate create call. Agent behavior rules (sequential per-group processing, `--paginate` on lists, verify with list commands after bulk writes, report all failures together) and the full 37-locale list are included. Honest caveats: requires Apple Developer membership and `asc` auth (`asc auth login` or `ASC_*` env vars) —...

- Listing: https://theskillharbor.com/products/rorkai-app-store-connect-cli-skills-asc-subscription-localization
- Fiche en français: https://theskillharbor.com/fr/products/rorkai-app-store-connect-cli-skills-asc-subscription-localization
- Category: Mobile
- Price: Free
- Verification: unverified
- Source repo: https://github.com/rorkai/app-store-connect-cli-skills/blob/main/skills/asc-subscription-localization/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-ramp
description: "Read-only view of corporate spend: transactions, cards and limits, users, departments."
---

# Ramp Connector for Muse

A Muse agent skill that inspects a Ramp corporate-spend account without any ability to move money: list and retrieve transactions, list cards with their spending restrictions, list users, and list departments. Read-only by design — it cannot issue cards, set limits, pay bills, or reimburse, because no write code path exists. Uses OAuth 2.0 client credentials with read-only scopes. Draft: written from Ramp's public developer docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-ramp
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-ramp
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/ramp

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

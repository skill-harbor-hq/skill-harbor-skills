<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-paddle
description: "View Paddle transactions and customers. Read-only by design."
---

# Paddle Connector for Muse

A Muse agent skill that reads your Paddle billing: list transactions (filter by status) and list customers. Read-only by design — it cannot create charges, refunds, or subscriptions, and it refuses any request to write. Uses a Paddle API key (live keys start with `pdl_live_`), kept in Muse's secure vault. Draft: written from Paddle's public Billing API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-paddle
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-paddle
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/paddle

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-etsy
description: "Read Etsy shop data: receipts, listings, transactions, payment ledger; create listings."
---

# Etsy Connector for Muse

A Muse agent skill that reads your Etsy shop: list receipts, list listings, list transactions, read the payment ledger. It can also create listings — a write that the skill confirms fully before running, because listing fees are real money (currently $0.20 per listing, 6.5% transaction fee, ~3% + $0.25 payment processing). Honest note: the API itself is free, but you need an approved Etsy developer app, which means building OAuth yourself — the skill's setup is explicit about the steps. Draft: written from Etsy's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-etsy
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-etsy
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/etsy

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

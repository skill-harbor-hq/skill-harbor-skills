<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-polar
description: "Read orders and customers; create checkouts and refunds."
---

# Polar Connector for Muse

A Muse agent skill that manages a Polar merchant store: read-only lookup of orders, subscriptions, products, customers, checkouts, and metrics; plus real money actions — create a checkout, create a product, and create a refund. Checkouts and refunds are HIGH actuations — the skill confirms exact-match before running them. Reading needs no confirmation. Honest note: Polar offers a sandbox environment to test against; the refund command creates a full refund of an order (no partial refund); Polar charges 4% + $0.40 per transaction with no monthly fee. Draft: written from Polar's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-polar
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-polar
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/polar

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-square
description: "Square seller account: locations, payments, orders, Terminal checkouts, charges, refunds."
---

# Square Connector for Muse

A Muse agent skill that works with a Square seller account: list locations and payments, create orders, push a checkout to a physical Square Terminal for in-person payment, charge a payment source directly, cancel a pending Terminal checkout, and refund a payment. Honest notes: sandbox is the default and is mandatory for testing — it never moves real money; Terminal checkout and direct charges are HIGH actuations (real funds) requiring exact-match confirmation on every call; refunds require confirmation every time. The API itself is free; Square charges processing fees per transaction. Draft: written from Square's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-square
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-square
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/square

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

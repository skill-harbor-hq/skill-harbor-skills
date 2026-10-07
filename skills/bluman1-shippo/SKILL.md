<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-shippo
description: "Ship through many carriers (USPS, UPS, FedEx, DHL and others) with one API: get rates for a..."
---

# Shippo Connector for Muse

A Muse agent skill that ships through many carriers with one API: get rates for a shipment, buy a printable postage label, track a parcel, refund unused labels. Test keys are the default path — they generate free test labels and nothing is billed; use them for every dry run. Production label purchase is HIGH: it buys real postage immediately and the account is billed — exact-confirmation gated, plus `--live` required. Refunds only work within carrier-specific windows and only for unused labels. There is no API fee: you pay the carrier postage. Uses a Shippo API token (Shippo dashboard), kept in Muse's secure vault. Draft: written from Shippo's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-shippo
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-shippo
- Category: E-commerce
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/shippo

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

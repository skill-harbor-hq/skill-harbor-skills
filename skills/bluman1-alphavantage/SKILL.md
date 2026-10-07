<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-alphavantage
description: "Stock quotes and daily price history. Read-only."
---

# Alpha Vantage Connector for Muse

A read-only Muse agent skill for stock market data: latest quote for a symbol and the last 5 daily closes. It never trades, never modifies anything, and never sends anything on your behalf. Respect the free tier (25 calls/day, 5/minute): batch symbols into as few calls as possible and never retry aggressively. Uses a free Alpha Vantage API key, kept in Muse's secure vault. This is market data, not financial advice. Draft: written from Alpha Vantage's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-alphavantage
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-alphavantage
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/alphavantage

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: coinpaprika-api
description: "Query prices, tickers, exchanges and historical OHLCV for thousands of cryptocurrencies, with a..."
---

# CoinPaprika API

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Market data is an input, not an edge: quotes can lag, differ between venues, and say nothing about what a price will do next. Curated by Skill Harbor: the vendor-published skill for the CoinPaprika API, from an independent crypto data aggregator operating since 2018 (12,000+ cryptocurrencies, 350+ exchanges). It teaches the agent the full surface: tickers and coin details, exchange listings and markets, historical OHLCV, global market statistics, through three integration routes (the REST API, the coinpaprika-cli command line tool, and a hosted MCP server for MCP clients). Access starts genuinely free: the public host needs no key and no registration, with 20,000 calls per month over 2,000 assets; paid tiers move to the pro host with an API key sent in the Authorization header (Starter at $99 per month up to Enterprise, per the pricing documented in the skill), and the skill is explicit that keys belong in environment variables, never hardcoded. A distinctive touch: the file opens with a freshness check that has the agent fetch the live version header and follow the newer copy if the versions differ, so a stale local skill does not quietly point at outdated endpoints. From the coinpaprika/skills repository (MIT). Honest caveats: the free tier covers 2,000 of the 12,000+ assets and the rate limit is 10 requests per second per IP across plans, so serious workloads reach the paid tiers...

- Listing: https://theskillharbor.com/products/coinpaprika-api
- Fiche en français: https://theskillharbor.com/fr/products/coinpaprika-api
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/coinpaprika/skills/blob/main/coinpaprika-api/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: dexpaprika-api
description: "Explore DEX data across 36 chains and 230+ DEXes: pools, tokens, swaps and live streams, keyless to..."
---

# DexPaprika API

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. On-chain DEX data describes a market where most tokens are illiquid, manipulated or worthless; a top-ranked pool is a data point, not a recommendation, and free-tier data is delayed by up to 60 seconds. Curated by Skill Harbor: the vendor-published skill for DexPaprika, the DEX data sibling of CoinPaprika, covering 36 blockchains, 230+ DEXes, 36M+ liquidity pools and 33M+ tokens (over 96% of on-chain DEX volume, per the vendor). It documents three integration routes with a clear recommendation for agents: the dexpaprika-cli (search, token and pool details, historical pool and token OHLCV, filtered token and pool queries, batch prices, and price streaming pushed when a swap moves the price), the REST API, and the SSE streaming service. Access is keyless to start (15 requests per minute on 10,000 credits over a rolling 30 days), a free registered key doubles the rate and multiplies the credits, and paid plans (Dev at $30 per month, Pro at $99, per the skill) serve real-time data from the pro host; some endpoints, like per-pool transactions and cross-pool token OHLCV, are paid-only. Like its sibling skill, the file opens with a freshness check against the live copy, and warns plainly that DexPaprika removes endpoints (they return HTTP 410) and reshapes responses, so stale copies point at dead ends. From the coinpaprika/skills repository (MIT). Honest caveats: both free routes serve data...

- Listing: https://theskillharbor.com/products/dexpaprika-api
- Fiche en français: https://theskillharbor.com/fr/products/dexpaprika-api
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/coinpaprika/skills/blob/main/dexpaprika-api/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

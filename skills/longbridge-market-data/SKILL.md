<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: longbridge-market-data
description: "Real-time quotes, K-lines, order book, capital flow, market sentiment, and IPO calendar for HK, US..."
---

# Longbridge Market Data

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A live quote is a snapshot, not a signal, and prices can move against you in seconds. Curated by Skill Harbor: the market data skill of the Longbridge platform, published by the broker itself. Through the Longbridge CLI it serves real-time quotes, K-line (OHLCV) charts, Level 2 order book depth and the Hong Kong broker queue, tick-by-tick trades, intraday minute charts, intraday capital distribution and flow, a market sentiment temperature index from 0 to 100, trading session schedules and market open or close status, security lists including overnight-eligible names, exchange rates, and the IPO calendar with subscription status for Hong Kong and the US. Two analysis frameworks ride on top of the data: ADR premium, which compares pricing of the same company across its US ADR, Hong Kong H-share and A-share listings, and FX carry, which works from spot rates, forward points and interest rate differentials. Almost every command is public and needs no login; live subscriptions need an active session token, and IPO orders or profit and loss views need the CLI auth login with trade permission. A Longbridge MCP server covers the same ground when the CLI is unavailable. From the longbridge/skills repository (MIT). Honest caveats: the figures are only as fresh and complete as the Longbridge feed for your market and session, delayed or closed-market snapshots are labeled as such only if you...

- Listing: https://theskillharbor.com/products/longbridge-market-data
- Fiche en français: https://theskillharbor.com/fr/products/longbridge-market-data
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/longbridge/skills/blob/main/skills/longbridge-market-data/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

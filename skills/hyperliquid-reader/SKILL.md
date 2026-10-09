<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-reader
description: "Read Hyperliquid perps and spot without an account: mark prices, funding in APR, open interest..."
---

# Hyperliquid Reader

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Perpetual futures are leveraged instruments where a funding screen or a pretty order book says nothing about the next move, and trading them carries a real risk of loss, up to liquidation. No output here is a promise of return, and a funding spread is a screen, not a guaranteed arbitrage: a real trade also pays exchange and withdrawal friction. Curated by Skill Harbor: a read-only market-data reader for Hyperliquid, the on-chain perps and spot exchange, built on opencli and this repo's own hyperliquid plugin. Every command is a single call to Hyperliquid's public info API, with no API key, no wallet, no login and no running app. It reads perp markets (mark, oracle and mid prices, 24-hour change, hourly funding and its annualized APR, open interest and 24-hour volume), spot pairs, all current mid prices, the L2 order book, OHLCV candles across intervals from one minute to one month, funding history, and its signature view, a cross-venue funding comparison that annualizes Hyperliquid, Binance and Bybit funding on their own intervals and ranks the widest spreads first, the starting point for funding-carry research. Output comes as table, JSON, YAML, Markdown or CSV, and the skill is told to lead with the headline number and filter hard (about 180 perps exist) rather than dump everything. From the himself65/finance-skills repository (MIT). Honest caveats: setup means Node.js 24 or later...

- Listing: https://theskillharbor.com/products/hyperliquid-reader
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-reader
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/data-providers/skills/hyperliquid-reader/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

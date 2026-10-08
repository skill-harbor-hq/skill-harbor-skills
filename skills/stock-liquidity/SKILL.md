<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: stock-liquidity
description: "Measure what a trade really costs: bid-ask spreads, average dollar volume, square-root market..."
---

# Stock Liquidity

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Liquidity figures are measurements and model estimates of trading costs, not a recommendation to trade or to avoid a stock. Curated by Skill Harbor: a liquidity workbench that answers the question quoted prices hide, namely what it actually costs to get in and out. Its dashboard combines the quoted bid-ask spread, average and median daily volume, average dollar volume, volume variability, turnover versus shares outstanding and free float, the Amihud illiquidity ratio, and a square-root market-impact estimate for an order of 1 percent of average daily volume, then rolls them into a plain-language liquidity grade from very high to very low. Focused routes cover spread analysis (including near-the-money options spreads as derivatives context), volume analysis (relative volume, trend, day-of-week profile), order-book depth proxies, market impact for a specific order size with a full impact curve across sizes, and turnover analysis with days-to-trade-the-float. It is especially pointed at small caps, penny stocks, and thin names, where these costs quietly eat returns. Data comes from Yahoo Finance through the free yfinance library. From the himself65/finance-skills repository (MIT). Honest caveats: you need Python 3 with pip (the skill installs yfinance, pandas, and numpy itself if missing); Yahoo Finance quotes are delayed about 15 minutes on most exchanges and show top of book only...

- Listing: https://theskillharbor.com/products/stock-liquidity
- Fiche en français: https://theskillharbor.com/fr/products/stock-liquidity
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/market-analysis/skills/stock-liquidity/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

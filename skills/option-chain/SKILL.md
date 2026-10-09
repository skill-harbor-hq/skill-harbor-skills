<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: option-chain
description: "The full call and put chain for a ticker and an expiry from Yahoo Finance: strikes, bids, asks..."
---

# Option Chain

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A chain shows quotes, not a recommendation, and option prices move fast. Curated by Skill Harbor: the full option chain for one ticker and one expiration, pulled from Yahoo Finance. Ask for the available expiration dates first, then fetch the chain itself: every call and put with strike, bid, ask, volume, open interest, and implied volatility, presented as a table next to the current underlying price, with the high-volume and high-open-interest strikes and notable IV levels highlighted. It is the raw material for the rest of the options toolkit in this repo: check liquidity before a trade, find the strikes that actually change hands, and see where the market is pricing movement. It runs as a Python script (scripts/options.py, needs pandas and yfinance) from the staskh/trading_skills repo, with all timestamps in New York time and a data delay field stamped on the output. From the staskh/trading_skills repository (MIT). Honest caveats: Yahoo Finance data is free but unofficial and can be delayed, stale, or missing strikes, so confirm any price you would act on with your broker; the chain covers one expiration at a time, and this is a data display, not a scanner across the whole market. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/option-chain
- Fiche en français: https://theskillharbor.com/fr/products/option-chain
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/option-chain/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

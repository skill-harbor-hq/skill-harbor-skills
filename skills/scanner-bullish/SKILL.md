<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: scanner-bullish
description: "Ranks your watchlist by bullish momentum: a composite score from moving averages, RSI, MACD and EMA..."
---

# Bullish Trend Scanner

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A high momentum score describes a trend that already happened; it is not a promise the trend continues. Curated by Skill Harbor: a momentum ranking for the watchlist you bring. Give it a comma-separated list of tickers and it scores each one, up to about 9.5 points, from price versus its 20 and 50 day moving averages, RSI bands, MACD position and histogram direction, EMA 9/21 and MACD crossovers and their freshness, ADX trend strength, and period momentum, then returns the names ranked strongest first with price, distance from the averages, the indicator values, the signals that fired, and the next earnings date and timing for each. Scores above 6 read as a strong bullish trend, 4 to 6 moderate, below 2 bearish or trendless, which turns the question of what looks good today into a sorted answer in one pass. It runs as a Python script (scripts/scan.py, needs pandas, pandas-ta, and yfinance) from the staskh/trading_skills repo. From the staskh/trading_skills repository (MIT). Honest caveats: it scans only the symbols you supply, not the whole market, so the ranking is only as good as the list you feed it; the score is a transparent heuristic, not a buy list, and trend tools lag at turning points and whipsaw in range-bound markets; Yahoo Finance data is unofficial and can be delayed. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/scanner-bullish
- Fiche en français: https://theskillharbor.com/fr/products/scanner-bullish
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/scanner-bullish/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

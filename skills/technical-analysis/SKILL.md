<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: technical-analysis
description: "RSI, MACD, Bollinger Bands, moving averages, ATR, and ADX for one ticker or a whole list, with..."
---

# Technical Analysis

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Indicators summarize the past; a bullish signal is not a forecast and fails regularly. Curated by Skill Harbor: a chartist's indicator panel computed for you, for one ticker or a comma-separated list. It calculates RSI, MACD, Bollinger Bands, SMA and EMA sets, ATR, and ADX over your chosen period with the pandas-ta library, reports the most recent MACD and EMA 9/21 crossovers and how many bars ago they happened, bundles volatility and Sharpe as risk metrics, and can attach upcoming earnings dates with EPS history. A companion script in the same skill builds a price correlation matrix across several symbols, the diversification check that shows whether your positions actually move independently or are secretly the same trade. Outputs come back as structured JSON with plain interpretation levels (RSI above 70 overbought, below 30 oversold, ADX above 25 a strong trend). It runs as Python scripts (scripts/technicals.py and scripts/correlation.py) from the staskh/trading_skills repo. From the staskh/trading_skills repository (MIT). Honest caveats: indicators generate heuristics, not predictions, and every signal here fires false positives, especially in sideways markets; Yahoo Finance data is unofficial and can be delayed, or adjusted differently than your broker's feed. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/technical-analysis
- Fiche en français: https://theskillharbor.com/fr/products/technical-analysis
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/technical-analysis/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: price-history
description: "Historical OHLCV price data for any stock from Yahoo Finance: pick the period and the interval..."
---

# Price History

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Past prices describe what already happened; a clean historical trend is not a forecast, and trading on one carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: historical OHLCV data (open, high, low, close, volume) for a stock, fetched from Yahoo Finance in the shape your question needs. The period runs from one day to the full available history (1d, 5d, 1mo, 3mo, 6mo, 1y, 2y, 5y, 10y, year to date, or max, with one month as the default) and the interval from one-minute bars to monthly bars (daily by default), returned as structured JSON with a date on every row. It is the raw material layer of this toolkit: the agent is told to read the series back as key movements, highs and lows, and trend, and the same data feeds chart work, back-of-envelope volatility checks, and the context for the scanner and risk skills listed alongside it. It runs as a Python script (scripts/history.py, needs yfinance) from the staskh/trading_skills repo, with timestamps in New York time and a data delay field stamped on the output. From the staskh/trading_skills repository (MIT). Honest caveats: Yahoo Finance history is free but unofficial, intraday intervals only reach back a limited number of days, splits and dividend adjustments can differ from your broker's series, and a one-minute series over a long period is a lot of rows to reason over, so match the interval to...

- Listing: https://theskillharbor.com/products/price-history
- Fiche en français: https://theskillharbor.com/fr/products/price-history
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/price-history/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

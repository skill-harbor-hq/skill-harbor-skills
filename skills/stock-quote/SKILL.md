<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: stock-quote
description: "A current quote for any ticker from Yahoo Finance: price, change, volume versus average, market..."
---

# Stock Quote

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A quote is a snapshot, not a recommendation: a stock up 3 percent today can be down 5 tomorrow, and acting on a headline number carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: the current quote for a ticker, fetched from Yahoo Finance and presented as a readable snapshot rather than raw JSON. One call returns the symbol and company name, the current price with the day's change in dollars and percent, today's volume against the average volume, market capitalization, the 52-week high and low, the P/E ratio and the dividend yield; the agent is told to present the data readably and to highlight significant moves, defined in the skill as a change beyond 2 percent. It is the quickest question in this toolkit (what is it trading at, and is today unusual) and the natural first step before the deeper chain, history or scanner skills. It runs as a Python script (scripts/quote.py, needs yfinance) from the staskh/trading_skills repo, with timestamps in New York time and a data delay field stamped on the output. From the staskh/trading_skills repository (MIT). Honest caveats: Yahoo Finance quotes are free but unofficial and can be delayed, so the price here is a reference, not an executable quote, and you should confirm it in your broker before any order; after-hours and pre-market moves may not be reflected the way a live feed shows them; and a single...

- Listing: https://theskillharbor.com/products/stock-quote
- Fiche en français: https://theskillharbor.com/fr/products/stock-quote
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/stock-quote/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

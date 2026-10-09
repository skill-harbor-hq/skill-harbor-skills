<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: fundamentals
description: "Financials, earnings, and key metrics from Yahoo Finance, plus a Piotroski F-Score that grades a..."
---

# Stock Fundamentals

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Strong reported numbers do not make a stock a good buy at any price, and a strength score is not a valuation. Curated by Skill Harbor: a company's reported numbers and a financial-strength grade in one pass. The main script pulls Yahoo Finance fundamentals for a ticker: key metrics (market cap, P/E, EPS, dividend), recent quarterly and annual income statement lines, and earnings history with estimates to compare against. A second included script computes the Piotroski F-Score, nine yes-or-no checks on profitability, cash flow quality, leverage, liquidity, dilution, margins, and asset turnover, each scored and shown, for a grade from 0 to 9 of financial strength, the screen value investors use to separate improving balance sheets from deteriorating ones. It runs as Python scripts (scripts/fundamentals.py and scripts/piotroski.py, needs pandas and yfinance) from the staskh/trading_skills repo. From the staskh/trading_skills repository (MIT). Honest caveats: Yahoo Finance figures are unofficial and can lag or differ from primary filings, so verify decision-critical numbers in the company's own reports; the F-Score's year-over-year checks need two years of annual data and are marked unavailable when the data is missing; a high score describes accounting strength, not a cheap price or a sound investment. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/fundamentals
- Fiche en français: https://theskillharbor.com/fr/products/fundamentals
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/fundamentals/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

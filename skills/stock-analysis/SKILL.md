<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: stock-analysis
description: "One stock, every angle: technicals, fundamentals, capital flow, news, and a seven-point risk screen..."
---

# Stock Analysis (All-in-One)

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Analysis frameworks organize information, they do not predict prices, and any stock can lose value. Curated by Skill Harbor: the flagship all-in-one analysis skill of the Weaxs stock-analysis-plugin. A bundled gather script pulls eight data sets in parallel (quote, candles, technicals, financials, capital flow, news, risk flags, market regime), then the skill works through them in order: the market environment first, then trend and signals (moving-average alignment, MACD, Bollinger position, volume behavior), valuation and profitability against history and sector, recent news, and a risk screen over seven dimensions (extreme valuation, technical warnings, lockup expiries, insider selling, earnings warnings, regulatory penalties, sector policy). The risk screen can raise a veto flag that must stay visible in the report. Output is a structured report, brief or full, and any buy or sell call must come with an observable trigger and an invalidation condition; the skill can also log its own calls and grade them later. From the Weaxs/stock-analysis-plugin repository (MIT). Honest caveats: the source SKILL.md is written in Chinese and the deepest data coverage targets mainland China A-shares; capital flow and parts of the risk screen simply do not exist for other markets, and the workflow says so rather than filling the gap with guesses; the data pipeline is the plugin's own multi-source...

- Listing: https://theskillharbor.com/products/stock-analysis
- Fiche en français: https://theskillharbor.com/fr/products/stock-analysis
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Weaxs/stock-analysis-plugin/blob/main/skills/stock-analysis/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: technical-analyst
description: "Pure chart-based technical analysis of weekly charts: trend, support and resistance, moving..."
---

# Technical Analyst

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Trading involves real risk of loss, and nothing in this skill places trades. Curated by Skill Harbor: a systematic technical-analysis workflow that reads weekly price chart images you provide (stocks, indices, cryptocurrencies, forex pairs) and deliberately ignores news, fundamentals, and sentiment. For each chart it works through a fixed sequence: trend direction and strength, horizontal and trendline support/resistance with confluence zones, price position versus the 20, 50, and 200-week moving averages, volume patterns, and chart patterns, then builds 2 to 4 probability-weighted scenarios with specific price targets and invalidation levels. Each analysis is saved as a markdown report in a reports/ folder, named by symbol and date. It loads its full methodology from the skill's included reference file (references/technical_analysis_framework.md), so bring that file along with the SKILL.md. No API keys are required; the only input is your chart images. From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: weekly timeframe only, and the output is only as good as the chart image you feed it (cropped or low-resolution charts degrade the levels). Pure chart reading by design means it will not warn you about an earnings release or a news shock that gaps the price through a level. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/technical-analyst
- Fiche en français: https://theskillharbor.com/fr/products/technical-analyst
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/technical-analyst/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

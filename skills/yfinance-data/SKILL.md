<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: yfinance-data
description: "The data-fetching foundation skill: pull Yahoo Finance quotes, price history, financial statements..."
---

# Yahoo Finance Data

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill fetches and presents market data; it draws no conclusions and makes no recommendations. Curated by Skill Harbor: the general-purpose data skill that the rest of the himself65 finance collection builds on. Give it a ticker and a need, and it routes to the right yfinance call and presents the numbers first, with the supporting table after: current quotes and price history, income statement, balance sheet, and cash flow (annual or quarterly), options chains, dividends and splits, earnings history, analyst estimates, price targets, ratings and upgrades or downgrades, institutional and insider holders, company overview and sector data, headline news, multi-ticker bulk downloads for comparisons, and stock screens. The practical rules that make the library behave are baked in: wrap calls in error handling because Yahoo can rate-limit or return empty frames, list option expirations before pulling a chain, respect intraday data limits, and handle the timezone-aware timestamps correctly. If your question is really an earnings preview or recap, a valuation, a correlation, a liquidity check, or an ETF premium question, the skill itself points you to the dedicated analysis skills in the same repository instead. From the himself65/finance-skills repository (MIT). Honest caveats: you need Python 3 with pip (the skill installs yfinance itself if missing); yfinance is an unofficial library...

- Listing: https://theskillharbor.com/products/yfinance-data
- Fiche en français: https://theskillharbor.com/fr/products/yfinance-data
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/market-analysis/skills/yfinance-data/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

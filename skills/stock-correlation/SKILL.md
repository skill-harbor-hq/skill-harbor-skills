<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: stock-correlation
description: "Find what moves with a stock: correlated peers discovered for you, pair correlation with beta and..."
---

# Stock Correlation

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Correlation describes how prices moved together in the past; it is not causation and it does not hold still. Curated by Skill Harbor: a correlation workbench with four routes. Co-movement discovery builds a peer universe for a single ticker at runtime with the Yahoo Finance screener (same industry first, then sector and adjacent themes, no hardcoded lists) and ranks the top correlated names with the reasons they might be linked. Pair analysis goes deep on two tickers: Pearson correlation, beta, R-squared, 60-day rolling correlation, and the log-price spread with its z-score for pairs and hedging work. Sector clustering computes the full matrix for a group and orders it with hierarchical clustering so blocks of tightly linked names become visible, outliers included. Realized correlation tracks how the relationship changes: rolling windows of 20, 60, and 120 days, plus regime splits for up days, down days, high volatility, and large drawdowns. Defaults are one year of daily log returns and a 0.60 correlation threshold. Data comes from Yahoo Finance through the free yfinance library, with pandas, numpy, and optionally scipy. From the himself65/finance-skills repository (MIT). Honest caveats: you need Python 3 with pip (the skill installs the libraries itself if missing); correlations famously spike toward 1 during sell-offs, so diversification measured in calm times can fail exactly when...

- Listing: https://theskillharbor.com/products/stock-correlation
- Fiche en français: https://theskillharbor.com/fr/products/stock-correlation
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/market-analysis/skills/stock-correlation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

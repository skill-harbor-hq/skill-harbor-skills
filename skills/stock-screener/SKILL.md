<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: stock-screener
description: "Screen a whole market down to a ranked shortlist: pick value, growth, trend, or custom filters, get..."
---

# Stock Screener

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A screen ranks the past, not the future, and every name on the list still needs its own analysis. Curated by Skill Harbor: a whole-market screening workflow from the Weaxs stock-analysis-plugin. You name the market (A-shares, Hong Kong, or US; A-shares by default), a style, and how many names you want back (Top 20 by default). A first quantitative pass filters the universe, an optional second pass re-scores candidates on quality, growth, true momentum, volatility, and capital-flow factors, and a final ranking weighs chart quality, volume-price behavior, indicator agreement, and distance to support. Every run also reports a market-sentiment temperature (0 to 100) with a multiplier that visibly tightens or loosens how aggressive the picks are. Preset templates cover value (low multiples, high ROE, steady dividends), growth, trend breakouts, and oversold reversals, or you can supply a custom YAML filter file. From the Weaxs/stock-analysis-plugin repository (MIT). Honest caveats: the source SKILL.md is written in Chinese and the defaults lean to mainland A-shares, where the factor data is richest; on other markets some factors are thinner and the sentiment gauge may rest on less data; screening is historical by construction, so treat the output as a research starting point. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/stock-screener
- Fiche en français: https://theskillharbor.com/fr/products/stock-screener
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Weaxs/stock-analysis-plugin/blob/main/skills/stock-screener/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

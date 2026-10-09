<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: report-stock
description: "One full stock report per ticker, in markdown or PDF: trend score, PMCC viability, fundamentals..."
---

# Stock Analysis Report

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. The report this skill produces ends in a BUY, HOLD or AVOID label computed from its own scores: that label is the output of a fixed scoring recipe over public data, not a professional recommendation, and acting on it carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: a full written stock analysis report for one or more tickers, generated from the other skills in this same repository. One script run per symbol gathers the pieces: company overview (sector, industry, market cap, beta), trend analysis from the bullish scanner (score, RSI, MACD, ADX, moving-average distances, the next earnings date), fundamentals (valuation, profitability, dividend and balance sheet, up to eight quarters of earnings history), the Piotroski F-Score with all nine criteria shown pass or fail, insider trading activity from public filings when data exists, PMCC viability (score, the LEAPS and short legs it would use, yield and capital required), and option spread strategies (bull call, bear put, straddle, strangle, iron condor). The agent then writes the report from the repo's markdown template into a dated file, and can convert it to PDF through the repo's markdown-to-pdf skill when you ask; the headline answer is the recommendation with its key strengths and risks and the saved report path. From the staskh/trading_skills repository (MIT). Honest caveats: the report is...

- Listing: https://theskillharbor.com/products/report-stock
- Fiche en français: https://theskillharbor.com/fr/products/report-stock
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/report-stock/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

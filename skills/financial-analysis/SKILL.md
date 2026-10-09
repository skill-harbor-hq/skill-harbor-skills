<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: financial-analysis
description: "Run a structured deep dive on a company's financials: normalized data, profitability, liquidity..."
---

# Financial Analysis

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. A health rating describes the statements in front of the analyst, not the future: companies that screen strong still fail, losses are possible on any decision taken from an analysis, and no output here is a promise of return. Curated by Skill Harbor: the financial analysis skill of GAJETOso/financeskills. Use it for a 10-K review, quarterly earnings, a profitability check, or simply when someone says look at these numbers. It starts by checking for corporate context files, then fixes the entity context (public or private, industry, reporting currency and period, GAAP, IFRS or local standard) and the goal of the analysis before touching the data. The framework runs in a set priority order: data extraction and normalization first (revenue, COGS, operating expenses, net income, non-recurring items identified, adjusted EBITDA where applicable), then profitability (gross, operating and net margins, ROE), liquidity (current ratio, quick ratio, days sales outstanding) and solvency (debt to equity, interest coverage), then efficiency ratios, then trend and anomaly detection. Trends are computed year over year and quarter over quarter, with acceleration and deceleration named, and any line item moving more than 15 percent without a clear footnote explanation is flagged, along with earnings management red flags such as revenue growing faster than cash flow. The report structure is fixed: an...

- Listing: https://theskillharbor.com/products/financial-analysis
- Fiche en français: https://theskillharbor.com/fr/products/financial-analysis
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/GAJETOso/financeskills/blob/main/skills/financial-analysis/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

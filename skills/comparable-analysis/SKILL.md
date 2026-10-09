<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: comparable-analysis
description: "Build a trading comparables set with cleaned EV/EBITDA, EV/EBIT and P/E multiples, a median..."
---

# Comparable Analysis

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. Market multiples move with the market, a comps read says where peers trade today and not what a business is worth in any absolute sense, and no implied range here is a promise of return. Curated by Skill Harbor: the trading comparables skill of the investment banking pack in andreworia/claude-finance-skills. Use it when you need a market read from public peers rather than an intrinsic estimate: sizing where the market prices a business today, sanity-checking a DCF, or setting an IPO or offer range. The method runs in eight steps. It defines the subject profile (sector, size, growth, margins) and screens a tight, defensible peer set, because a short clean set beats a long loose one. It pulls the market and financial data each multiple needs (share price, diluted shares, net debt, LTM and forward EBITDA, EBIT and EPS), then cleans for comparability: non-recurring items stripped, stock-based compensation and lease treatment standardized across the set, fiscal years calendarized to a common end. It computes enterprise value correctly and keeps numerator and denominator consistent (EV pairs with EBITDA and EBIT, equity value pairs with EPS), spreads EV/EBITDA, EV/EBIT and P/E on LTM and forward bases so outliers show, and summarizes the set with median, mean and interquartile range, preferring the median where the set is small or skewed. Finally it applies the low, median and high...

- Listing: https://theskillharbor.com/products/comparable-analysis
- Fiche en français: https://theskillharbor.com/fr/products/comparable-analysis
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andreworia/claude-finance-skills/blob/main/packs/investment-banking/skills/comparable-analysis/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

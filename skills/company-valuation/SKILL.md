<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: company-valuation
description: "What is a stock worth? DCF, peer multiples, and sum-of-the-parts blended into one implied price..."
---

# Company Valuation

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Valuation outputs are model estimates built on assumptions, not predictions or recommendations. Curated by Skill Harbor: a full intrinsic-value workflow that triangulates three methods instead of trusting one. It builds a DCF (five-year free-cash-flow projection discounted at a WACC assembled from a live 10-year Treasury rate, beta, and an equity risk premium), a relative valuation (peer median forward P/E, EV/Revenue, and EV/EBITDA applied to the company), and a sum-of-the-parts when the company reports two or more distinct segments, then blends them into one implied share price with upside or downside versus the market. Every run includes a 5x5 WACC by terminal-growth sensitivity grid and bull, base, and bear scenarios, plus sanity gates that flag an implausible WACC or a terminal value dominating the result. It runs as real Python on Yahoo Finance data through the free yfinance library, using the methodology in its included reference files (DCF, relative valuation, SOTP, and WACC and rate tables). From the himself65/finance-skills repository (MIT). Honest caveats: you need Python 3 with pip (the skill installs yfinance, numpy, and pandas itself if missing); yfinance data is unofficial and can lag or be wrong, so cross-check decision-critical figures against primary filings; a DCF is only as good as its assumptions, which is why the sensitivity grid matters more than the single...

- Listing: https://theskillharbor.com/products/company-valuation
- Fiche en français: https://theskillharbor.com/fr/products/company-valuation
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/market-analysis/skills/company-valuation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

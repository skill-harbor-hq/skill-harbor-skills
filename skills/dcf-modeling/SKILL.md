<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: dcf-modeling
description: "Build a discounted cash flow model with a CAPM-based WACC, terminal value computed two ways, and a..."
---

# DCF Modeling

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. A DCF is only as good as its forecast and its discount rate: small changes in WACC or terminal growth move the answer a lot, and no model output here is a promise of return or a guarantee that a price is right. Curated by Skill Harbor: the discounted cash flow skill of the investment banking pack in andreworia/claude-finance-skills. Use it when value should be driven by what a business generates rather than what the market currently pays: a thin or noisy peer set, a business in transition that multiples miss, or a fundamentals-anchored cross-check on comps. The method runs in eight steps. It projects unlevered free cash flow year by year (EBIT taxed at the marginal rate to NOPAT, plus depreciation and amortization, minus capex and the increase in net working capital, usually over 5 to 10 years), builds the cost of equity with CAPM and the after-tax cost of debt, blends them into WACC at target or market weights rather than book values, then computes terminal value two ways, Gordon growth and an exit EV/EBITDA multiple, and reconciles them by stating the growth the multiple implies and the multiple the growth implies. It discounts the flows and the terminal value (mid-year convention noted where used), bridges enterprise value to equity value per share (net debt, minority interest, preferred, non-operating assets, diluted shares on a treasury-method basis), and finishes with a...

- Listing: https://theskillharbor.com/products/dcf-modeling
- Fiche en français: https://theskillharbor.com/fr/products/dcf-modeling
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andreworia/claude-finance-skills/blob/main/packs/investment-banking/skills/dcf-modeling/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

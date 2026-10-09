<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: capital-structure
description: "Read and reshape a debt and equity mix: leverage and coverage metrics, a WACC estimate at market..."
---

# Capital Structure

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. A target structure is an analytical conclusion, not an instruction to borrow or repay: leverage decisions carry real default and covenant risk, and no metric or comparison here is a promise of return or a recommendation to restructure. Curated by Skill Harbor: the capital structure skill of the investment banking pack in andreworia/claude-finance-skills. Use it when you need to read a company's existing mix of debt and equity or reshape it toward a target: assessing debt capacity for an acquisition, evaluating a refinancing, or advising on whether a balance sheet is under or over-levered. The method runs in eight steps. It builds the current structure by instrument in priority order (each debt tranche with balance, coupon, maturity and security, then equity by class), computes net debt with gross and net shown separately so the cash position stays visible, and calculates leverage on normalized EBITDA (net debt to EBITDA, plus gross and capex-adjusted variants where relevant) with any add-backs noted, since aggressive adjustments flatter leverage. Interest coverage tests how comfortably the company services debt through a downturn. The cost of each component follows: after-tax cost of debt per tranche using the coupon and the tax shield, cost of equity via CAPM, blended into WACC at market-value weights, with an explicit pitfall warning against book weights, and the inputs stated so...

- Listing: https://theskillharbor.com/products/capital-structure
- Fiche en français: https://theskillharbor.com/fr/products/capital-structure
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andreworia/claude-finance-skills/blob/main/packs/investment-banking/skills/capital-structure/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

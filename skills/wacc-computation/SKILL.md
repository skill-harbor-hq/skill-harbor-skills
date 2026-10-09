<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: wacc-computation
description: "Compute the weighted average cost of capital with a CAPM cost of equity, beta unlevering and..."
---

# WACC Computation

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. WACC is the discount rate and the hurdle rate at once, so a small error in it quietly reprices every valuation and project decision downstream: an understated WACC approves projects that destroy value and overstates what a business is worth, losses follow from decisions taken on it, and no figure here is a promise of return. Curated by Skill Harbor: the WACC computation skill of GAJETOso/financeskills, written from the seat of a corporate finance manager. Use it when a valuation or capital budgeting decision needs its discount rate: cost of equity, cost of debt, CAPM, beta unlevering, risk-free rate or equity risk premium questions all route here. The assessment gathers the capital structure at market values (market value of equity, market value of debt or book value as a stated proxy, preferred stock where it exists), the CAPM inputs (risk-free rate, beta raw or to be unlevered and relevered, equity risk premium), and the cost of debt (pre-tax yield to maturity or marginal borrowing rate, and the marginal tax rate). The framework runs in priority order: data collection, cost of equity by CAPM, after-tax cost of debt, weighting at market values, never book values, then the final computation with sensitivity. The formula blends the three sources: equity weight times cost of equity, plus debt weight times after-tax cost of debt, plus preferred weight times its cost where present. The...

- Listing: https://theskillharbor.com/products/wacc-computation
- Fiche en français: https://theskillharbor.com/fr/products/wacc-computation
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/GAJETOso/financeskills/blob/main/skills/wacc-computation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

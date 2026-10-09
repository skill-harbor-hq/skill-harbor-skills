<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: three-statement-modeling
description: "Build or debug an integrated three-statement model where every line traces to a labeled driver, the..."
---

# Three-Statement Modeling

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. A model organizes assumptions, it does not validate them: an integrated model built on wrong drivers is precisely wrong, losses are possible on any decision taken from it, and no output here is a promise of return. Curated by Skill Harbor: the three-statement modeling skill of GAJETOso/financeskills. Use it to build or debug a model where the income statement, balance sheet and cash flow statement link correctly, or when someone says the balance sheet does not balance or a circular reference will not resolve. The build order is fixed. It starts with a drivers and assumptions sheet, every assumption in one labeled place with historical context, then builds the income statement (revenue by price times volume, cohort or segment, never a bare growth rate without basis, costs split variable, fixed and stepped, down through EBITDA, depreciation from the asset schedule, interest from the debt schedule, tax, to net income), then the supporting schedules: PP&E rollforward, working capital driven by DSO, DIO and DPO days, debt schedule, and equity rollforward. The balance sheet is driven entirely by those schedules with nothing hardcoded, and the cash flow statement is derived entirely from income statement and balance sheet deltas, its cash feeding the balance sheet cash line. The revolver plug handles the cash sweep logic (draw the shortfall below minimum cash, repay when excess cash exists)...

- Listing: https://theskillharbor.com/products/three-statement-modeling
- Fiche en français: https://theskillharbor.com/fr/products/three-statement-modeling
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/GAJETOso/financeskills/blob/main/skills/three-statement-modeling/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

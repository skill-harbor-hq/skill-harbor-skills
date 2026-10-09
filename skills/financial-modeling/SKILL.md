<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: financial-modeling
description: "Build an integrated three-statement model from explicit drivers, fully linked, with the circularity..."
---

# Financial Modeling

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. A model organizes assumptions, it does not validate them: a fully linked model built on a wrong growth or margin assumption is precisely wrong rather than roughly right, and no output here is a promise of return. Curated by Skill Harbor: the financial modeling skill of the investment banking pack in andreworia/claude-finance-skills, the base skill the pack's DCF and LBO work stands on. Use it when the income statement, balance sheet and cash flow statement must move together off shared drivers: underwriting a company for a deal, refreshing a client model, or building the base for a valuation. The method runs in eight steps. It sets the model spine first (historicals restated into one clean consistent format, standard three years of history and a five-year forecast), builds the income statement from explicit drivers so every line is a formula off an assumption cell and never a hardcode inside the statement, then builds the supporting schedules that feed the statements: the fixed-asset roll-forward, the working-capital schedule off days ratios, and the debt schedule. The balance sheet rolls every line from its driver or schedule, with an explicit warning never to plug it directly because a plug hides a broken link, and the cash flow statement reconciles net income to the change in cash, which must flow into the balance-sheet cash line. The interest and debt circularity is closed with a...

- Listing: https://theskillharbor.com/products/financial-modeling
- Fiche en français: https://theskillharbor.com/fr/products/financial-modeling
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andreworia/claude-finance-skills/blob/main/packs/investment-banking/skills/financial-modeling/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

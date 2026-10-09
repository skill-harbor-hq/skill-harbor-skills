<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: lbo-returns-analysis
description: "Structure an LBO returns case in bear, base and bull scenarios, with MOIC and IRR sensitivity to..."
---

# LBO Returns Analysis

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. Scenario returns are arithmetic on assumptions, not forecasts: leverage amplifies the bear case as readily as the bull case, a downside scenario can breach covenants and wipe out equity, there is a real risk of loss in any buyout, and no IRR or MOIC here is a promise of return. Curated by Skill Harbor: the LBO returns analysis skill at the root of andreworia/claude-finance-skills. Distinct from the investment banking pack LBO modeling skill (lot 86), which builds the full model with its debt schedule and value creation bridge, and from the private equity pack LBO structuring skill (lot 89): this skill structures the returns logic, the scenario set and the sensitivity analysis that a live model must contain, ahead of an indicative bid, a final bid or an investment committee memo. The method builds sources and uses first, on quality of earnings adjusted EBITDA rather than management adjusted figures, then defines bear, base and bull cases that stay internally consistent across four operating dimensions (revenue growth, EBITDA margin, capex and working capital, each with its own downside mechanics such as churn driven revenue for subscription businesses or a margin floor for labour intensive ones). It then lays out the debt schedule per tranche with amortization, rate assumptions and prepayment terms, computes free cash flow after debt service per scenario, sets the exit with the base...

- Listing: https://theskillharbor.com/products/lbo-returns-analysis
- Fiche en français: https://theskillharbor.com/fr/products/lbo-returns-analysis
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andreworia/claude-finance-skills/blob/main/skills/lbo-returns-analysis/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

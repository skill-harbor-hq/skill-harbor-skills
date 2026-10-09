<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: lbo-modeling
description: "Build an LBO model with sources and uses, a debt schedule with cash sweep, and IRR and MOIC returns..."
---

# LBO Modeling

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. An LBO model tests whether a buyout clears a return hurdle on paper; leverage magnifies losses as readily as gains, real deals can and do lose money, and no return figure here is a promise of return. Curated by Skill Harbor: the leveraged buyout skill of the investment banking pack in andreworia/claude-finance-skills. Use it when the question is what a financial buyer can pay and still hit its hurdle: assessing a sponsor price, setting a floor in a valuation range, or stress-testing leverage and returns. The method runs in eight steps. It sets the entry (entry enterprise value as a multiple of LTM EBITDA, transaction date, hold period, commonly five years), builds sources and uses that must tie (uses: purchase equity value, refinanced debt, fees; sources: debt tranches sized to a leverage target in turns of EBITDA, sponsor equity as the plug), projects the operating case down to free cash flow available for debt paydown, builds a debt schedule per tranche with mandatory amortization, cash interest and an optional cash sweep of excess cash applied in priority order, resolves the interest circularity explicitly (iterative calculation or a circuit-breaker toggle), sets the exit (exit multiple applied to exit-year EBITDA, with the base case held flat because assuming expansion is aggressive), computes both IRR and MOIC since a high multiple on a long hold can still miss the IRR hurdle...

- Listing: https://theskillharbor.com/products/lbo-modeling
- Fiche en français: https://theskillharbor.com/fr/products/lbo-modeling
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andreworia/claude-finance-skills/blob/main/packs/investment-banking/skills/lbo-modeling/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

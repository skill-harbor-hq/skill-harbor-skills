<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: merger-analysis
description: "Test whether a proposed acquisition is accretive or dilutive: pro-forma EPS, the breakeven premium..."
---

# Merger Analysis

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. Accretive does not mean good and dilutive does not mean bad: this analysis is a first quantitative screen on earnings per share, it says nothing about whether a deal creates value over time, and no output here is a promise of return. Curated by Skill Harbor: the merger analysis skill of the investment banking pack in andreworia/claude-finance-skills. Use it whenever a deal team asks whether a combination lifts or hurts EPS, or wants to test a price, a consideration mix or a synergy assumption before a board discussion or a pitch. The method runs in nine steps. It collects standalone figures for acquirer and target (net income, diluted shares, EPS, forward figures preferred since deals are marketed on next-twelve-months earnings), sets the purchase price from the offer per share times fully diluted shares plus the control premium over the unaffected price, and fixes the consideration mix across cash, new debt and stock, checked against leverage capacity so pro-forma leverage stays inside covenants. It layers the financing effects at the marginal borrowing rate (after-tax incremental interest on debt, foregone interest on cash spent), layers expected synergies after tax with their phasing and their one-time costs to achieve, computes the new share count from the stock portion, and builds pro-forma net income as a clean adjustment-by-adjustment bridge, including incremental amortization...

- Listing: https://theskillharbor.com/products/merger-analysis
- Fiche en français: https://theskillharbor.com/fr/products/merger-analysis
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andreworia/claude-finance-skills/blob/main/packs/investment-banking/skills/merger-analysis/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

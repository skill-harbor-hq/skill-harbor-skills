<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: longbridge-skills-longbridge-portfolio
description: "Read account assets, positions, P&L and statements, manage buy/sell/cancel orders and DCA, run..."
---

# Longbridge portfolio, orders and analysis (real-money trading)

Curated by Skill Harbor. WARNING: Real-money trading. This skill can place, replace and cancel live orders on your brokerage account. Mutating commands do NOT share one preview rule: orders are dry run by default and need a confirmation code re-run, DCA changes take effect immediately with no dry run, and fund submit and cancel orders have no dry run and need a validate-order preview confirmed exactly before running with --yes. DCA is AP accounts only, not Longbridge US accounts, and several commands differ or are unavailable on US accounts. Treat previews as final check gates. @longbridge's official skill for the Longbridge brokerage terminal: read account net assets, cash, buying power and margin breakdown; list stock and fund positions, P&L, cash-flow records, withdrawals and deposits and account statements; get margin-ratio requirements and max buy and sell quantity estimates; manage orders (buy, sell, cancel, replace), fund orders and DCA recurring investments; and run analysis frameworks: portfolio diagnosis, rebalancing plans, asset allocation, risk analysis (VaR and CVaR, drawdown, Sharpe and Calmar), Brinson performance attribution and tax-loss harvesting with wash-sale tracking. Honest caveats: positions, fund-positions, statement and bank-cards need Trade permission; orders, fund orders and DCA need Trade permission and a live login (longbridge auth login); margin-ratio and max-qty work without login; trading commissions and margin costs follow Longbridge's own...

- Listing: https://theskillharbor.com/products/longbridge-skills-longbridge-portfolio
- Fiche en français: https://theskillharbor.com/fr/products/longbridge-skills-longbridge-portfolio
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/longbridge/skills/blob/main/skills/longbridge-portfolio/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

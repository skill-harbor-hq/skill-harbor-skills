<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: sam-hui-dot-mcd-budget-meal-mcd-budget-meal
description: "Three priced McDonald's China pickup meals inside your budget, checked against live prices and your..."
---

# McDonald's Budget Meal

A single person pickup meal planner for McDonald's China. From one sentence (budget, store or location, must have items, items to avoid, pickup time) it builds at most three candidate meals from the live menu and your store coupons, prices every candidate with the official calculate-price tool, and compares them locally: payable total, budget left, and the coupon or member conditions used. It is read and price only by design: its direct MCP client allows exactly five tools (query-nearby-stores, query-meals, query-store-coupons, query-meal-detail, calculate-price) and refuses everything else. It never orders, pays, claims coupons, redeems points or adds an address. A batch run can save the quotes and a local HTML report in a private records folder on your machine.

- Listing: https://theskillharbor.com/products/sam-hui-dot-mcd-budget-meal-mcd-budget-meal
- Fiche en français: https://theskillharbor.com/fr/products/sam-hui-dot-mcd-budget-meal-mcd-budget-meal
- Category: Food & Drink
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Sam-Hui-dot/mcd-budget-meal

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

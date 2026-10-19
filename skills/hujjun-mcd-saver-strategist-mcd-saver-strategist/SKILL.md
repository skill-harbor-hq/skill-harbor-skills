<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hujjun-mcd-saver-strategist-mcd-saver-strategist
description: "Find the cheapest valid McDonald's China order for your budget, using every coupon on your account..."
---

# McDonald's Saver Strategist

A savings optimizer for McDonald's China orders. It pulls the live menu, prices, nutrition and every coupon pool for your store from the McDonald's China MCP (menu, claimable McMaiSheng coupons, coupons already on your account, and store coupons), then runs a deterministic local optimizer (scripts/optimizer.py, Python standard library only) that exhausts the combinations and returns the cheapest valid order for your wants, budget, calorie limit and party size, with a coupon audit, top up advice and a price and calorie Pareto front. Its workflow calls auto-bind-coupons as a required step, which claims all claimable McMaiSheng coupons to your account before optimizing. Only on your explicit confirmation does it recheck the price with calculate-price and place the order with create-order, returning the payment link.

- Listing: https://theskillharbor.com/products/hujjun-mcd-saver-strategist-mcd-saver-strategist
- Fiche en français: https://theskillharbor.com/fr/products/hujjun-mcd-saver-strategist-mcd-saver-strategist
- Category: Food & Drink
- Price: Free
- Verification: unverified
- Source repo: https://github.com/hujjun/mcd-saver-strategist

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

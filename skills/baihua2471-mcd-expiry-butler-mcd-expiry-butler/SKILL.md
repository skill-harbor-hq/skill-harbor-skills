<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: baihua2471-mcd-expiry-butler-mcd-expiry-butler
description: "See which McDonald's China coupons and points are about to expire, which are worth using inside..."
---

# McDonald's Expiry Butler

A read only butler for expiring McDonald's China benefits. It lists the coupons usable at your chosen store that expire soon (seven day window by default), reads your points balance including the points expiring this month and next, and answers one question for each benefit: is it worth using, inside the budget and the meal you actually want? Every candidate plan is priced with the official calculate-price trial, and only a successful trial counts as a verified price. It returns at most two plans, and when nothing clears your budget and channel it says so plainly and recommends not using the benefit at all, instead of pushing you to spend before an expiry date. Its judgement rules run in a local Python program with no network code (expiry windows, channel matching, budget filtering), which renders the result as a local HTML report. It is forbidden by its own red lines from claiming coupons, redeeming points, ordering, cancelling, drawing or changing an address.

- Listing: https://theskillharbor.com/products/baihua2471-mcd-expiry-butler-mcd-expiry-butler
- Fiche en français: https://theskillharbor.com/fr/products/baihua2471-mcd-expiry-butler-mcd-expiry-butler
- Category: Food & Drink
- Price: Free
- Verification: unverified
- Source repo: https://github.com/baihua2471/mcd-expiry-butler

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

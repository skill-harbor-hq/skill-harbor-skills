<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-inventory-demand-planning
description: "Retail demand-planning expertise codified: forecasting methods, ABC/XYZ segmentation, safety stock..."
---

# Inventory Demand Planning

Curated by Skill Harbor: a senior demand planner's playbook, codified for multi-location retailers running 40 to 200 stores with regional distribution centers and 300 to 800 active SKUs. It covers the full loop: collecting and cleansing demand signals, selecting the forecasting method per SKU from the ABC/XYZ classification and demand pattern (moving averages for stable staples, Holt-Winters for seasonal items, STL decomposition when seasonality shifts, causal regression when price and promos drive demand, LightGBM or XGBoost only when you have 1,000+ SKUs times 2+ years of history and an ML team), applying promotional lifts with cannibalization offsets, computing safety stock from demand and lead-time variability with honest service-level math (moving from 95% to 99% service nearly doubles safety stock, so it makes you price that decision), generating purchase orders with MOQ and EOQ rounding, and monitoring forecast accuracy on MAPE, WMAPE, bias, and tracking signal. It also handles the edge cases textbooks skip: lumpy intermittent demand via Croston's method and bootstrapped distributions, new products via analog-SKU mapping with a 20 to 30% buffer for the first 8 weeks, and post-promo dip planning. By @affaan-m (skill authored by evos), listed here with credit to its creator. From the affaan-m/ECC repository; this skill declares its own license, Apache-2.0. Honest caveats: written for planners with real POS, ERP, and WMS data; without your demand history it becomes a...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-inventory-demand-planning
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-inventory-demand-planning
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/inventory-demand-planning/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

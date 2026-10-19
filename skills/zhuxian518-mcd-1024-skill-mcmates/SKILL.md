<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: zhuxian518-mcd-1024-skill-mcmates
description: "One McDonald's China answer, not fifteen: a pick that fits your budget and nutrition goal, priced..."
---

# McMates

A single answer McDonald's China ordering friend. You state a want, a budget and a nutrition goal, and it returns exactly one recommended combination with a three line reason (nutrition met, price after coupons, why this one), plus two backups drawn from your own history: an old friend (your most frequent recent order) and a new taste (an item in your favourite taste cluster that you have never ordered). It keeps a local memory bank (data/memory.json in the skill folder: your orders, taste clusters, average spend and favourite stores) that only grows, and it maintains a daily Big Mac price index: on the first recommendation of each day it silently samples Big Mac and medium fries prices in two or three cities and appends them to a local snapshot, which feeds one daily price fact and, on request, a full city price table. Prices always come from the official calculate-price check, never from its own estimates.

- Listing: https://theskillharbor.com/products/zhuxian518-mcd-1024-skill-mcmates
- Fiche en français: https://theskillharbor.com/fr/products/zhuxian518-mcd-1024-skill-mcmates
- Category: Food & Drink
- Price: Free
- Verification: unverified
- Source repo: https://github.com/zhuxian518/mcd-1024-skill

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

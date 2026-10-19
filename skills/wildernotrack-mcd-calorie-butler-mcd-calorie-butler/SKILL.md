<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: wildernotrack-mcd-calorie-butler-mcd-calorie-butler
description: "Eat McDonald's China inside your calorie goal: a local food log, a remaining budget, a priced plan..."
---

# McDonald's Calorie Butler

A calorie butler for people who want McDonald's China while cutting, maintaining or bulking. You tell it what you ate today (McDonald's items use the official nutrition table; other food is estimated by the agent and always labelled as an estimate), and it keeps a local profile and food log under ~/.mcd-calorie-butler on your machine: daily calorie and protein goals, taste notes you state once, your usual store and your usual order. scripts/butler.py does every number locally (log, remaining calories per meal, taste to calorie cost ranking, planning), the McDonald's China MCP provides nutrition, menus, meal details and official pricing, and the result is a priced plan that fits what is left today. Ordering happens only when you explicitly say to order: create-order is then called with the priced items, and payment is completed by you on the official McDonald's page. Its fetch script is read only and refuses write tools.

- Listing: https://theskillharbor.com/products/wildernotrack-mcd-calorie-butler-mcd-calorie-butler
- Fiche en français: https://theskillharbor.com/fr/products/wildernotrack-mcd-calorie-butler-mcd-calorie-butler
- Category: Food & Drink
- Price: Free
- Verification: unverified
- Source repo: https://github.com/WilderNoTrack/mcd-calorie-butler

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

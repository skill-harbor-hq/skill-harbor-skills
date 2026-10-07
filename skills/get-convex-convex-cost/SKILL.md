<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: get-convex-convex-cost
description: "Preview what your Convex app will cost — cost drivers ranked, growth curves, cheapest fix named"
---

# Convex Cost Preview

💳 Curated by Skill Harbor — makes Convex spend legible before it surprises you: it reads the deployment's own bytes/documents-read evidence via the official MCP, attributes it to the functions driving it, ranks cost drivers by bytes/documents read per call times observed call volume (the product is the driver — a cheap-per-call function called constantly can outweigh an expensive rare one), and projects how each top driver scales — a full-table `.collect()` grows linearly with the table, an indexed `.take(n)` stays flat. It names the cheapest fix and carries the confirm-cost discipline: before anything metered, it states the price and gets an explicit yes. No traffic yet? It estimates from query shapes instead. Honest prerequisites: cost evidence comes from cloud insights, which needs a Convex Cloud deployment on a paid plan. Distinct from convex-insights (the observability wrapper it draws on) and convex-billing (adding Stripe, not reading spend). By @get-convex, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/get-convex-convex-cost
- Fiche en français: https://theskillharbor.com/fr/products/get-convex-convex-cost
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/get-convex/agent-skills/blob/main/skills/convex-cost/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: observation-marketplace
description: "Watch the market, buy nothing yet."
---

# Observation Marketplace

Observation Marketplace turns a classified market into an observatory, in read only mode. You define a watchlist once, with a regional centre, a radius, and queries by category and priority, then you capture regular snapshots and keep them as they are. From those snapshots, you get three honest views: price by precise category and model, lifecycle by first view, last view and number of passes seen, and seller by number of listings and store signals.

Two guards keep the views honest. Trap prices, such as 0 and 9999, are filtered before any median, and medians are used instead of averages on mixed groups. A disappearance is never counted, on its own, as a sale: a sale and a withdrawal without a sale are two distinct outcomes, classified separately. A store seller, recognised by signals such as stock numbers, taxes or inventory, is labelled as such and excluded from private seller price references. Furniture, large appliances and bulky items are filtered out.

Nothing here buys, contacts or spends. Every judgement stays on paper, every real purchase, real contact or change of scope needs a separate explicit decision, and no existing snapshot job is modified by this skill.

Important, stated in the skill itself: this draft is pending the review on 30 October 2026. Do not assume that the system continues after that review. Phase 3 has no fixed content in this draft, and phase 2 needs a separate go.

- Listing: https://theskillharbor.com/products/observation-marketplace
- Fiche en français: https://theskillharbor.com/fr/products/observation-marketplace
- Category: Data
- Price: Free
- Verification: verified
- Source repo: n/a

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

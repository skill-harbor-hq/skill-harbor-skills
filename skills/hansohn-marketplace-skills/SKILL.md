<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hansohn-marketplace-skills
description: "Draft eBay and Facebook listings from your inventory, never publish by accident."
---

# Marketplace Skills for Muse

Marketplace Skills drafts listings for eBay and Facebook Marketplace from what you already have: photos and an inventory list. Muse compares similar sold items to price yours, writes the title and description, and prepares the photos to match. Four skills cover the job: price comps, eBay drafts, listing files, and photos.

It only ever drafts. It never publishes anything, never automates a browser (eBay forbids it), and always asks before any authenticated eBay call. The eBay side needs the eBay MCP server plus free eBay developer credentials and a Seller Hub setup — that leg was not tested here, no account was used.

Caveats:
- The eBay auto-draft needs the eBay MCP server (YosefHayim/ebay-mcp) + free eBay developer credentials + Seller Hub setup (inventory location, policies). **Not tested** — no eBay account was used.
- Prices are in USD by default.
- Facebook publishing is impossible via API — the skill says so: manual copy.
- Live comps via Playwright MCP and end-to-end listing generation inside Claude Code were not tested (no Claude Code on the test PC).

- Listing: https://theskillharbor.com/products/hansohn-marketplace-skills
- Fiche en français: https://theskillharbor.com/fr/products/hansohn-marketplace-skills
- Category: E-commerce
- Price: Free
- Verification: verified
- Source repo: https://github.com/hansohn/marketplace-skills

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

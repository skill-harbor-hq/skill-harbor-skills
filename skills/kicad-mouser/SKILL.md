<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad-mouser
description: "Search Mouser as the second prototype source, for price comparison and parts DigiKey does not carry."
---

# Mouser Parts Search

Curated by Skill Harbor: the second prototype source in the KiCad collection, used deliberately as a complement to DigiKey rather than a duplicate. Reach for it when DigiKey is out of stock or has worse pricing, when comparing prices across distributors, or when searching for parts DigiKey does not carry. It finds parts, checks pricing and stock, downloads datasheets, analyzes specifications, and syncs a local datasheets directory for a KiCad project, with batch part-number list seeding for bulk work without a project. It also documents the Mouser Search API response structure and a package cross-reference table, and it feeds parametric data to the SPICE skill for behavioral models, like the other distributor skills. By @aklofas, listed here with credit to its creator. Honest caveats: the API method needs Mouser API credentials from an account, stored as environment variables, never pasted into a chat; a website fallback exists but is less reliable than the API; and DigiKey remains the preferred datasheet source in this collection because its API returns direct PDF links. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad-mouser
- Fiche en français: https://theskillharbor.com/fr/products/kicad-mouser
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/mouser

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

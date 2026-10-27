<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad-element14
description: "Search Newark, Farnell and element14 through one API for parts, pricing, stock and datasheets."
---

# element14 Parts Search

Curated by Skill Harbor: the international distributor skill in the KiCad collection. One API covers three regional storefronts with the same catalog and the same datasheets, only pricing and stock varying by region: Newark for the US, Farnell for the UK and EU, and element14 for Asia Pacific. It finds parts by manufacturer part number or distributor part number, checks pricing and stock, downloads datasheets directly from the Farnell content delivery network, and syncs a local datasheets directory for a KiCad project, with batch part-number list seeding for bulk work without a project. Its main practical advantage over the other distributor skills is the simple credential setup: a free API key with query-parameter authentication, no OAuth flow. By @aklofas, listed here with credit to its creator. Honest caveats: the free key still comes from a developer account and must live in an environment variable, never in a chat; regional pricing means the same part can show different prices across storefronts, so compare before ordering; and a website fallback exists but is less reliable than the API. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad-element14
- Fiche en français: https://theskillharbor.com/fr/products/kicad-element14
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/element14

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

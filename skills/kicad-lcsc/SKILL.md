<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad-lcsc
description: "Search LCSC by part number or keyword for production sourcing, with JLCPCB assembly compatibility..."
---

# LCSC Parts Search

Curated by Skill Harbor: the production sourcing skill in the KiCad collection. LCSC is JLCPCB's sister company, so the two share the same parts library and the same C-number part numbers, which makes LCSC the natural source when a board will be assembled by JLCPCB. It finds components by LCSC number or manufacturer part number, checks stock and pricing, downloads datasheets, analyzes specifications, and syncs a local datasheets directory for a KiCad project, with batch part-number list seeding for bulk work without a project. It also covers cross-referencing and finding equivalents when a part is missing, and the differences from DigiKey and Mouser, which the collection positions for prototypes instead. By @aklofas, listed here with credit to its creator. Honest caveats: the community search API used by default needs no API key, but the official LCSC API requires approval, so do not assume official API access; a website fallback exists but is less reliable; and production quantities deserve the same price and stock recheck as prototypes before ordering. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad-lcsc
- Fiche en français: https://theskillharbor.com/fr/products/kicad-lcsc
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/lcsc

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

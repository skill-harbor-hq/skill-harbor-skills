<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad-digikey
description: "Search DigiKey by keyword or part number, check price and stock, and download datasheets through..."
---

# DigiKey Parts Search

Curated by Skill Harbor: the primary prototype sourcing skill in the KiCad collection. It searches DigiKey for electronic components by keyword or manufacturer part number, checks pricing and stock, and downloads datasheets through the DigiKey Product Information API, which returns direct PDF links, making it the preferred datasheet source in this collection. It also syncs and maintains a local datasheets directory for a KiCad project, extracting components from schematics, downloading missing datasheets and keeping them up to date, and it supports batch part-number list seeding for bulk work without a KiCad project. For production orders the collection points at LCSC instead, DigiKey is positioned for prototypes. By @aklofas, listed here with credit to its creator. Honest caveats: the API method needs DigiKey API credentials from a developer account, stored as environment variables, never pasted into a chat; a website fallback exists but is less reliable than the API; and prices and stock are a snapshot at search time, always recheck before ordering. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad-digikey
- Fiche en français: https://theskillharbor.com/fr/products/kicad-digikey
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/digikey

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

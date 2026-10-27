<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad-bom
description: "Run the full bill of materials lifecycle from a KiCad schematic, across all distributors, to..."
---

# BOM Management

Curated by Skill Harbor: the workflow skill that holds an electronics bill of materials together. It treats the KiCad schematic symbol properties as the single source of truth, then runs the full lifecycle: analyze the schematic, search distributors, validate parts, write properties back into the schematic, export tracking spreadsheets, and generate order files. It coordinates the distributor and fabrication skills in this batch rather than replacing them, so a search for a part at one distributor, a price comparison, or a fabrication order all flow through one BOM instead of scattered notes. It also covers the awkward corners: package and footprint cross-references, BOM diffing between revisions, interactive BOM views, and a production readiness checklist before anything is ordered. By @aklofas, listed here with credit to its creator. Honest caveats: it assumes a real KiCad schematic to work from, it is not a parts database on its own; distributor searches need the distributor skills and their credentials; and it prepares orders, it does not place them for you, so final quantities and prices still need a human eye. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad-bom
- Fiche en français: https://theskillharbor.com/fr/products/kicad-bom
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/bom

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

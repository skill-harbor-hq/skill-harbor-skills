<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad-datasheets
description: "Pull structured specs out of component datasheet PDFs and cache them for schematic, EMC and SPICE..."
---

# Datasheet Extraction

Curated by Skill Harbor: the extraction layer the rest of the KiCad collection depends on. It takes component datasheet PDFs, usually downloaded into a project datasheets folder by one of the distributor skills, and pulls out structured specifications: pinouts, electrical characteristics, peripherals, topology and features. Extractions are cached per project, so schematic, EMC and SPICE analysis can look up verified component knowledge (pin thresholds, power-good signals, peripheral speeds) instead of re-reading a PDF every time. It is deliberately a producer of facts for other skills, not a standalone reviewer: it extracts and verifies what a datasheet says, and hands the result to the analyzers. By @aklofas, listed here with credit to its creator. Honest caveats: it needs PDFs to work from, it does not fetch them itself, pair it with a distributor skill for that; extraction quality depends on the PDF, scanned or poorly structured datasheets will need a human check; and cached extractions should be refreshed when a datasheet revision changes. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad-datasheets
- Fiche en français: https://theskillharbor.com/fr/products/kicad-datasheets
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/datasheets

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

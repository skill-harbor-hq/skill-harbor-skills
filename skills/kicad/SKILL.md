<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad
description: "Deep analysis of KiCad schematics, PCB layouts, Gerbers and PDF schematics, with evidence-backed..."
---

# KiCad Project Analysis

Curated by Skill Harbor: the central skill of the KiCad collection, and by far the largest (about 10,400 words). It reads KiCad projects end to end: schematics, PCB layouts, footprints, symbols, netlists and design rules, plus PDF schematics from development boards, reference designs and evaluation kits. It reviews a design for bugs, traces nets, cross-checks schematic against PCB, extracts bill of materials data, and checks design rule checks, electrical rule checks, design for manufacturing, power trees and regulator circuits. Every finding carries a confidence label and an evidence source, with a trust summary rollup, so a review reads as checked claims rather than guesses. It supports KiCad 5 through 10, and it is the hub the other skills in this batch plug into: the distributor skills feed it part data, and the EMC and SPICE skills build on its analysis. By @aklofas, listed here with credit to its creator. Honest caveats: the SKILL.md is very long, so an agent with a small context window will struggle with the full file; distributor lookups need their own API credentials (see the distributor fiches); and a review is guidance for an engineer, not a substitute for a final human check before fabrication. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad
- Fiche en français: https://theskillharbor.com/fr/products/kicad
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/kicad

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: earthtojake-text-to-cad-cad
description: "Create and edit parametric 3D CAD models with build123d — Python models, STEP/STL/3MF/GLB/xbf..."
---

# Parametric CAD modeling with build123d (cadgen)

Curated by Skill Harbor — @earthtojake's CAD modeling skill: write Python models as parameterless @model functions returning build123d shapes, run the script to rebuild in cadgen's warm engine (the open page updates; files are exports made on request with cadgen export to STEP, STL, 3MF, GLB or xbf), organize projects, resolve prompt references (document-id refs like <id>#bracket/face 7, plus file refs in each file's own terms) into owned geometry for measurement and inspection, run checks with native build123d geometry and cadgen.geometry, snapshot documents for OCCT-rendered visual review, articulate mechanisms (build123d joints, cadgen.ap242) and animate (cadgen.gltf animation()). Updated October 28, 2026: re-pinned to cadgen 0.8.1 — the 0.8 engine replaces the old pipeline (no compatibility layer: a project written for 0.7 does not run on 0.8 without migration, see the migrations reference; keep a 0.7 STEP to compare placements); 0.8.1 brings build123d 0.13, OCP 8 and native materials (bd_materials); setup corrected — cadgen now runs through its installed launcher (cadgen +0.8.1, installed once via the uvx doctor command) with its engine server, and snapshots are rendered by OCCT, with no headless-browser download. Honest caveats: millimetres and +Z up unless the task says otherwise; geometry must stay deterministic (a function of code and inputs only: clock, environment and randomness are not seen); never read a model's own output or a project-exported file as its...

- Listing: https://theskillharbor.com/products/earthtojake-text-to-cad-cad
- Fiche en français: https://theskillharbor.com/fr/products/earthtojake-text-to-cad-cad
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/earthtojake/text-to-cad/blob/main/skills/cad/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: earthtojake-text-to-cad-cad
description: "Create and edit parametric 3D CAD models with build123d — Python models, STEP/STL/3MF/GLB/xbf..."
---

# Parametric CAD modeling with build123d (cad)

Curated by Skill Harbor — @earthtojake's CAD modeling skill: write Python models as parameterless @model functions returning build123d shapes, run the script to rebuild in text-to-cad's server (the open page updates; files are exports made on request with cad export to STEP, STL, 3MF, GLB or xbf), organize projects, resolve prompt references (document-id refs like <id>#bracket/face 7, plus file refs in each file's own terms) into owned geometry for measurement and inspection, run checks with native build123d geometry, snapshot documents for visual review, articulate mechanisms (build123d joints, cad.ap242) and animate (cad.gltf animation()). Updated November 2, 2026: re-pinned to text-to-cad 0.10.0 — the tool is renamed from cadgen to cad: install with the texttocad.dev script (outside a sandbox or with its permission), one server runs for the installation, and cad doctor explains the installation; commands are now cad run, cad export and cad snapshot. Honest caveats: millimetres and +Z up unless the task says otherwise; geometry must stay deterministic (a function of code and inputs only: clock, environment and randomness are not seen); never read a model's own output or a project-exported file as its input, compose by calling models; 2D DXF work belongs to a separate skill; listed here with credit to its creator; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

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

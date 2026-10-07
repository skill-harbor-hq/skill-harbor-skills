<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: earthtojake-text-to-cad-cad
description: "Create and edit parametric 3D CAD models with build123d — Python decorators, STEP/STL/3MF/GLB..."
---

# Parametric CAD modeling with build123d (cadgen)

Curated by Skill Harbor — @earthtojake's CAD modeling skill: write plain Python scripts with parameterless decorated functions returning build123d shapes, edit the source and rerun to regenerate outputs; organize projects (src/, STEP/, declared outputs, a model catalog), export meshes (stack @stl/@threemf/@glb for maintained outputs, or one-off `cadgen stl/3mf/glb build` from an existing STEP), resolve prompt references like `assembly.step#o1.2.f7` into owned geometry for measurement and inspection, run checks with native build123d geometry and cadgen.geometry (kept in checks/, exploratory ones in ignored tmp/), snapshot STEP or mesh outputs for visual review, and repair failures in source with the model's rebuild diagnostics (`cadgen store why`, `--force`). Setup: pip install the skill's requirements.txt with the active interpreter, plus Chromium via Playwright for rendering; `cadgen doctor` verifies the package pin and CAD kernel. Honest caveats: millimeters and XY/+Z unless the task says otherwise; geometry must stay deterministic (no dependence on time, random values, environment or working directory); never read a model's own output as its input; 2D DXF work belongs to a separate skill; listed here with credit to its creator; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

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

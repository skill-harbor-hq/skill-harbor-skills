<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: martinholovsky-claude-skills-generator-glsl
description: "GLSL shader expertise — TDD-first workflow with visual regression tests, GPU performance patterns..."
---

# GLSL shader programming — holographic effects, TDD workflow

Curated by Skill Harbor — @martinholovsky's GLSL shader-programming skill: GPU-side expertise for holographic visual effects (the JARVIS HUD theme is framing — the techniques are generic). A TDD-first implementation workflow: write failing tests first (shader compilation, uniform accessibility, visual regression against baselines, UV edge cases), implement the minimum to pass, then refactor to the full shader and run the full verification suite (`test:shaders`, `test:visual`, `bench:shaders`, cross-browser WebGL compat). Performance patterns with ❌/✅ pairs: branchless math (mix/step over if/else), texture atlases to cut draw calls, distance-based LOD for noise octaves, uniform batching into vectors/matrices, precision matching to data needs, caching texture lookups. Safety standards: constant loop bounds always (dynamic bounds can hang the GPU), guard every division, limit texture sizes. Includes ready recipes (holographic panel with scanlines, energy field, data-visualization bars) and a pre-commit checklist. Honest caveats: methodology only — the agent needs a WebGL/GLSL project to apply it to; the author declares risk level LOW (GPU code has limited attack surface but can freeze the system if careless). Unlicense (public-domain dedication). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/martinholovsky-claude-skills-generator-glsl
- Fiche en français: https://theskillharbor.com/fr/products/martinholovsky-claude-skills-generator-glsl
- Category: Design
- Price: Free
- Verification: unverified
- Source repo: https://github.com/martinholovsky/claude-skills-generator/blob/main/skills/glsl/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

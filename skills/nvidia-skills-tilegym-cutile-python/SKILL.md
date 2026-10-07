<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: nvidia-skills-tilegym-cutile-python
description: "Step-by-step kernel design (tile sizes, type annotations, launch), mandatory compile-run-validate..."
---

# cuTile GPU kernel programming: tile-based kernels with validation and orchestration workflows

Curated by Skill Harbor — @nvidia's cuTile programming skill: the full workflow for writing high-performance GPU kernels in cuTile's tile-based Python DSL — search TileGym's `src/tilegym/ops/cutile/` for existing examples BEFORE implementing (then the packaged `examples/`), assess complexity (single kernel → simple workflow; 3+ kernels or inter-kernel dependencies → deep agent-orchestration pipeline with Op Tracer → Analyzer → parallel Kernel Agents → Composer), follow the mandatory steps (understand the problem, design tile/block sizes as powers of 2, annotate every constant with `ct.Constant[type]`, keep the forward path pure cuTile with `@ct.kernel` + `ct.launch` — no `nn.*`/`F.*` compute in `forward()`), and run the mandatory validation loop (generate → execute → fix, up to 3 attempts) against a PyTorch reference. Four critical rules anchor correctness: pure cuTile forward path, tile indices not element indices, power-of-2 tile dimensions, typed constants. Honest caveats: needs an NVIDIA GPU with cuTile installed to validate anything; a specialized skill for kernel authors, not for general Python users; the SKILL.md frontmatter also names CC-BY-4.0 alongside Apache-2.0 (license field varies by source — review before redistributing). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/nvidia-skills-tilegym-cutile-python
- Fiche en français: https://theskillharbor.com/fr/products/nvidia-skills-tilegym-cutile-python
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/nvidia/skills/blob/main/skills/tilegym-cutile-python/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

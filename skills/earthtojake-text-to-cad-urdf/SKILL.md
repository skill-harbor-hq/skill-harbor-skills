<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: earthtojake-text-to-cad-urdf
description: "Author and validate URDF robot descriptions — frame semantics, inertials, mesh references, cadgen..."
---

# URDF robot description authoring and validation

Curated by Skill Harbor — @earthtojake's URDF skill: treat robot descriptions as constrained kinematic modeling, not XML writing. Author the `.urdf` directly as the source of truth (no Python generation pipeline), open with a design ledger as a comment block (frames, joints, geometry, units, assumptions), get joint-origin/link-frame/joint-axis semantics exactly right, compute — never freehand — inertia tensors and derived numbers (closed-form formulas for primitives, throwaway helper scripts for mesh-derived values), validate every created or modified file with `cadgen urdf validate` (XML structure, tree topology, joint semantics including limits/mimic/dynamics, geometry, mesh references, materials, inertial physics; `--strict` and `--json` modes), snapshot robots to PNG for a joint-by-joint viewer sweep, and hand completed work to `$cad-viewer` when installed. Setup: pip install the skill's requirements.txt with the active interpreter; Chromium via Playwright for snapshots; `cadgen doctor` verifies the installed cadgen matches the skill's pin. Honest caveats: robots are authored in metres; link meshes must be present — an unhydrated Git LFS pointer fails validation; validation is a guardrail, not spatial proof — the ledger and viewer sweep exist for that; use the SRDF skill for MoveIt2 semantics and the CAD skill for STEP/STL outputs; listed here with credit to its creator; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via...

- Listing: https://theskillharbor.com/products/earthtojake-text-to-cad-urdf
- Fiche en français: https://theskillharbor.com/fr/products/earthtojake-text-to-cad-urdf
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/earthtojake/text-to-cad/blob/main/skills/urdf/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

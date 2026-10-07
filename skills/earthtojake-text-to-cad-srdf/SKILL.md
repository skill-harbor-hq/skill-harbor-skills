<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: earthtojake-text-to-cad-srdf
description: "Author, validate and smoke-test MoveIt2 SRDF planning semantics — planning groups, end effectors..."
---

# SRDF authoring and validation for MoveIt2 robots

Curated by Skill Harbor — @earthtojake's SRDF skill for MoveIt2: author and edit the `.srdf` XML directly (planning semantics, not robot structure) with a strict workflow — start from a valid URDF, extract the link/joint table first and never type names from memory, define virtual/passive joints, planning groups derived from URDF topology, end effectors with correct group membership, group states in URDF-native units (radians, meters, within URDF limits), and disabled-collision pairs generated from evidence rather than invented — then validate everything with `cadgen srdf validate` (cross-validates names, chains, states and collisions against the paired URDF) and hand the file to the CAD viewer skill for live review. Companion to the sibling URDF, SDF and cad-viewer skills from the same repo. Honest caveats: niche robotics workflow — needs Python with the cadgen distribution (`pip install -r requirements.txt`), a valid URDF as starting point, and a headless browser (playwright chromium) for snapshots; the skill is one piece of a multi-skill authoring suite; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/earthtojake-text-to-cad-srdf
- Fiche en français: https://theskillharbor.com/fr/products/earthtojake-text-to-cad-srdf
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/earthtojake/text-to-cad/blob/main/skills/srdf/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-blender-motion-state-inspection
description: "Debug Blender characters with Muse: extract structured scene state first (bones, axes, contacts..."
---

# Blender Motion State Inspection

Curated by Skill Harbor: an inspection workflow for Blender characters, rigs, and retargeted motion that refuses to judge from screenshots alone. Screenshots hide axis conventions, bone names, object scale, local transforms, parented meshes, and frame-by-frame contact state, so the skill extracts structured facts first (via a state exporter or a Blender Python script run through blender --background, since bpy only exists inside Blender's own interpreter), then uses renders to confirm what the facts imply. The workflow inventories the scene, maps the skeleton with semantic bones, resolves forward/up/side axes (watching for glTF Y-up versus Blender Z-up mismatches), samples the frames most likely to expose problems, checks model integrity before blaming retargeting, and diagnoses ground penetration, foot sliding, leg crossover, twist damage, and scale drift with practical thresholds (1 to 2 cm penetration, 5 percent scale change, 30 degree heading jumps). Reports separate confirmed facts from visual suspicions with frame numbers and coordinates. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: you need Blender and the actual scene file, screenshots alone will not do; it diagnoses, it does not repair meshes unless you explicitly ask. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-blender-motion-state-inspection
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-blender-motion-state-inspection
- Category: 3D
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/blender-motion-state-inspection/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

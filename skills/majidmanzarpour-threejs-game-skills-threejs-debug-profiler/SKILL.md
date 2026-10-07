<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: majidmanzarpour-threejs-game-skills-threejs-debug-profiler
description: "Triage Three.js browser games — reproduce first, find the module that owns the failure, fix the..."
---

# Three.js debug profiler: blank canvases, runtime bugs and measured bottlenecks

Curated by Skill Harbor — @majidmanzarpour's Three.js debug-and-profile skill for browser games: a lead-scoped workflow. Debug: reproduce first with the same command and URL the user had, read console/page/network errors, find the module that owns the failure (renderer, loop, camera, scene, assets, audio, input, physics, UI, base path), fix the root cause there, and retest the exact broken path — with an ordered triage playbook (blank canvas, asset and audio loading, loop/animation/physics, input and mobile) covering common causes like duplicate active loops, canvas display size mismatched with the drawing buffer, and wrong delta units. Profile: baseline one fixed production scenario, classify the bottleneck (CPU, GPU draw, fragment, vertex, memory or network), change one thing, re-measure the same scenario, confirm visuals and playability held — across draw calls, triangles, textures, memory, shader and post-processing cost, and bundle size. Report: root cause or measured bottleneck first, then files changed, baseline/post metrics, commands, screenshots, the broken path retested, and residual risks. Honest caveats: methodology plus a detailed debug playbook — reads as part of an agent-led project structure (a "lead" consolidates verification); the reference playbook's diagnostic shape is specific to this skill family. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/majidmanzarpour-threejs-game-skills-threejs-debug-profiler
- Fiche en français: https://theskillharbor.com/fr/products/majidmanzarpour-threejs-game-skills-threejs-debug-profiler
- Category: Game Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/majidmanzarpour/threejs-game-skills/blob/main/skills/threejs-debug-profiler/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

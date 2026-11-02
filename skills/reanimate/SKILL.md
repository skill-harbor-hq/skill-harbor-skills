<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: reanimate
description: "Clone a reference animation frame by frame, then prove it matches."
---

# reanimate

reanimate rebuilds what the user points at so that it moves the way the reference moves, and proves it with a frame-by-frame comparison, never with "it looks about right". The deliverable is code in the user's project plus evidence (numbers and side-by-side sheets). First, pick a fidelity level and state it: motion-faithful by default (trigger, sequence and order, stagger, timing of every step within 80 ms, easing family, direction and distance relative to element size, layout proportions may keep the user's own copy, colours, fonts, images, and brand details), pixel-faithful when the user asks for an exact match (plus fonts, sizes, colours, spacing, radii, shadows, and assets, with mean frame mismatch at or under 2 percent), or mixed when the user adds their own content on top. The workflow lives in .reanimate/<name>/ inside the user's project: scope (target, destination, fidelity), setup, capture of the reference, a motion spec with one row per element per property, build in the user's stack, then verify, fix, and repeat, capturing the clone with the exact command used for the reference. It covers CSS and JS motion as well as canvas, WebGL, WebGPU, and three.js and 3D scenes. Loop until every spec row passes, expecting 2 to 5 rounds; if after 5 rounds a row still fails, stop and report it with its numbers and reason, never quietly lower the threshold or drop the row. Limits as written: when a reference is a login-walled page or a YouTube or Loom link that cannot be...

- Listing: https://theskillharbor.com/products/reanimate
- Fiche en français: https://theskillharbor.com/fr/products/reanimate
- Category: Animation
- Price: Free
- Verification: unverified
- Source repo: https://github.com/NiazMorshed2007/reanimate

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

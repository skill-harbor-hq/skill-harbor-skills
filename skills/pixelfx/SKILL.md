<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pixelfx
description: "Make pixel art effects and sprite animations in code."
---

# pixelfx

Pixel art effects as code: each effect is one file, src/fx/<category>/<name>.js, that draws into two buffers, color, with opaque, dithered or truly translucent pixels, and light, an additive glow. There are no images, so an effect can be played live, recolored, mirrored, reseeded and rendered to a sprite sheet for any engine. The method is Hugo Duprez's: code is clay, trust your eyes, feed your references. One-shot prompts make mediocre effects, while drafts that are rendered, looked at and refined make good ones.

Before anything, work in a pixelfx checkout, or clone one next to the project if the working directory has no tools/render.mjs. There is no install step: the tools use only Node. Checking it runs means rendering fire/torch and opening its contact sheet, which is how every effect is seen from then on. First, look for an existing effect: list tools search ids, names, tags and descriptions, and the catalog lists everything by category. Render the candidates and look at them before choosing, since most requests are an existing effect with different options, such as palette, seed, flip, angle, light strength, plus each effect's own knobs.

To put an effect in a game, canvas or WebGL games in JS or TS use the code directly, with no dependencies, copying src/core and the effect files needed, or depending on the repo. Any other engine, Godot, Unity, GameMaker, Defold, LOVE, Bevy or Construct, uses exported sprite sheets: a transparent frame grid plus an Aseprite-style...

- Listing: https://theskillharbor.com/products/pixelfx
- Fiche en français: https://theskillharbor.com/fr/products/pixelfx
- Category: Game development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/patch-gg/pixelfx

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

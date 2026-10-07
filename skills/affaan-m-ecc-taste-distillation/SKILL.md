<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-taste-distillation
description: "Measure reference videos into a reusable style pack: 3D LUT, cut rhythm, stills, and overlay plates."
---

# Taste Distillation

Curated by Skill Harbor: turn reference videos into a reusable, deterministic style pack. The core finding, measured on real footage: prompting cannot deliver a grade, measurement can. The skill ships working Python scripts that mint one pack per genre: chroma measured by luminance zone (median plus MAD, never mean plus std), contrast as the standard deviation of L*, background-share statistics, adaptive shot-boundary detection for the cut-rhythm distribution, a baked 33^3 .cube LUT that drops straight into DaVinci Resolve, hero stills, screen-blend overlay plates lifted onto black, minted 3D props, and a VLM-written spec grounded in the measurements. mint.py runs fully offline with no API key; only the fal-backed stages need credentials plus an explicit allow-live flag, and --dry-run stubs every network call. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: you need Python and reference footage you have the rights to analyze; keep each genre in its own pack. Pair with taste-application to generate against the pack. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-taste-distillation
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-taste-distillation
- Category: Video
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/taste-distillation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

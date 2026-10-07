<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-taste-application
description: "Generate new video against a distilled style pack and cut it into a finished, numerically verified..."
---

# Taste Application

Curated by Skill Harbor: the second half of the TasteForge pipeline. taste-distillation measures references into a style pack; this skill generates new video against that pack and cuts it into a finished piece. The division of labour is measured, not stylistic: the model supplies content, motion, and lighting structure while the pack supplies color and rhythm, so generation prompts contain zero color language ("Colour: none. Render neutral. Grading is applied afterwards."). It covers economical take-based generation (group shots into ~5s takes instead of one generation per shot), re-encode cutting rules, anchored tone grading, fal.ai endpoint picks with real prices, the 3D prop branch (Blender), numerical verification of the finished cut (background share, chroma error, cadence), and an editable FCPXML/EDL timeline handoff for Resolve. The bundled scripts are a working implementation, not pseudocode. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: generation stages run on fal.ai and cost real money; always start with --dry-run (free, no credentials) and verify endpoint prices before a paid run. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-taste-application
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-taste-application
- Category: Video
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/taste-application/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

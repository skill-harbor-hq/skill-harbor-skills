<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: prime-skills-video-inpainting
description: "Region edits across video frames — remove objects, clean wires, replace regions with matching motion"
---

# Video Inpainting

💳 Curated by Skill Harbor — region edits across video frames on RunComfy via the `runcomfy` CLI: remove an object that appears across many frames, clean up wires or watermarks, replace a region with motion that matches the rest of the clip. Routes across Wan 2-7 edit-video (default, prompt-driven region edits with spatial language), Lucy Edit Restyle (identity-stable region-aware restyle), and Seedream 4-0 edit-sequential (when treating the clip as a frame stack) — picking the right route for prose-driven, identity-locked, or frame-by-frame chained changes. Distinct from its sibling prime-skills-video-outpainting: inpainting edits regions *inside* the moving frame; outpainting extends the canvas *around* it. Requires a RunComfy account, the RunComfy CLI (`npm i -g @runcomfy/cli`), and generation calls are billed against API credits — a paid service. Honest notes: the source docs use RunComfy's "Pro Pack" marketing voice and carry tracking links; the technical content (endpoints, schemas, examples) is real and documented. By @prime-skills, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/prime-skills-video-inpainting
- Fiche en français: https://theskillharbor.com/fr/products/prime-skills-video-inpainting
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/prime-skills/runcomfy-agent-skills/blob/main/video-inpainting/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: prime-skills-image-inpainting
description: "Mask-driven region edits — remove objects, fill gaps, replace areas on RunComfy"
---

# Image Inpainting

💳 Curated by Skill Harbor — mask-driven image inpainting on RunComfy via the `runcomfy` CLI: remove objects, fill gaps, replace masked areas. Routes to Tongyi MAI Z-Image Turbo Inpainting (the dedicated inpainting endpoint with mask, strength, and control-scale) when a mask is available, and to identity-preserving edit models (Nano Banana 2 Edit, GPT Image 2 Edit, FLUX Kontext Pro) when the region must be described in prose instead. Use for object removal, watermark removal, region replacement, blemish cleanup — any controlled local edit where a binary mask defines the target area. Distinct from its sibling prime-skills-image-outpainting: inpainting edits *inside* the frame; outpainting extends *beyond* it. Requires a RunComfy account, the RunComfy CLI (`npm i -g @runcomfy/cli`), and generation calls are billed against API credits — a paid service. Honest notes: the source docs use RunComfy's "Pro Pack" marketing voice and carry tracking links; the technical content (endpoints, schemas, examples) is real and documented. By @prime-skills, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/prime-skills-image-inpainting
- Fiche en français: https://theskillharbor.com/fr/products/prime-skills-image-inpainting
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/prime-skills/runcomfy-agent-skills/blob/main/image-inpainting/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

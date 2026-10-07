<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-fal-ai-media
description: "Generate images, videos and audio through fal.ai MCP models — Nano Banana, Seedance, Kling, Veo 3..."
---

# AI media generation via fal.ai (image, video, audio)

Curated by Skill Harbor — 💳 **Paid API required / API payante requise** — fal.ai generations are billed per run through your FAL API key; there is no ongoing usable free tier. @affaan-m's unified media-generation skill routes through the fal.ai MCP server: text-to-image and editing with Nano Banana 2 (fast) and Nano Banana Pro (high fidelity), text/image-to-video with Seedance 1.0 Pro, Kling Video v3 Pro and Veo 3, text-to-speech with CSM-1B, video-to-audio with ThinkSound, plus an ElevenLabs REST fallback for professional voice synthesis — with a `search`/`find`/`estimate_cost` discovery flow and a strict discipline of checking cost before generating, using seeds for reproducibility, and iterating on cheap models before final renders. Honest caveats: requires the fal.ai MCP configured with your own `FAL_KEY` (keep it in the vault); video jobs are async — poll status; third-party models are subject to fal.ai's own terms. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-fal-ai-media
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-fal-ai-media
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/.agents/skills/fal-ai-media/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

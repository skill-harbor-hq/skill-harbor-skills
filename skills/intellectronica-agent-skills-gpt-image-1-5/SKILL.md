<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: intellectronica-agent-skills-gpt-image-1-5
description: "Generate and edit images with OpenAI's GPT Image 1.5 — text-to-image with quality/size/background..."
---

# GPT Image 1.5 — generate and edit images

💳 **Paid API required** — Curated by Skill Harbor — @intellectronica's skill for generating and editing images with OpenAI's GPT Image 1.5 model. Invoke it for any generate/create/edit request: generation goes through the Responses API's `image_generation` tool, edits use the Image API for reliable mask-based inpainting (without mask = full-image edit via an auto-generated transparent mask). A `generate_image.py` script takes prompt, filename (timestamped `yyyy-mm-dd-hh-mm-ss-name.png` pattern), quality (low/medium/high), size (1024x1024, 1024x1536, 1536x1024, auto) and background (transparent/opaque/auto) options, plus `--input-image`/`--mask` for edits; the agent never reads the image back — it just reports the saved path. Honest caveats: requires a paid OpenAI API key (`--api-key` argument or `OPENAI_API_KEY` env var — save it in your secure vault, never paste a live key here); always run from the user's current working directory so images land where the user works. CC0-1.0 licensed (public domain dedication). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/intellectronica-agent-skills-gpt-image-1-5
- Fiche en français: https://theskillharbor.com/fr/products/intellectronica-agent-skills-gpt-image-1-5
- Category: Image Generation
- Price: Free
- Verification: unverified
- Source repo: https://github.com/intellectronica/agent-skills/blob/main/plugins/gpt-image-1-5/skills/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

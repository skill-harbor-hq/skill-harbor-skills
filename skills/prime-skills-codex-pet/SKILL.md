<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: prime-skills-codex-pet
description: "Generate a custom Codex Pet spritesheet + pet.json from a single reference image via RunComfy"
---

# Codex Pet

💳 Curated by Skill Harbor — build a Codex-compatible custom Codex Pet: from a single reference image, produce the exact pet atlas Codex expects (1536×1872 PNG/WebP, 8 cols × 9 rows, 192×208 cells, 9 animation states — idle, running-right, running-left, waving, jumping, failed, waiting, running, review) as `spritesheet.webp` + `pet.json`, drop it into `${CODEX_HOME:-$HOME/.codex}/pets/<name>/`, and Codex picks it up next to the 8 built-ins. Calls OpenAI GPT Image 2 edit once via the local RunComfy CLI (`runcomfy run openai/gpt-image-2/edit`) to produce a canonical character sheet, then post-processes with ImageMagick. The most whimsical of the 15 prime-skills: a creative toy, not a media pipeline. Requires a RunComfy account, the RunComfy CLI (`npm i -g @runcomfy/cli`), ImageMagick, and generation calls are billed against API credits — a paid service. Honest notes: the source docs use RunComfy's "Pro Pack" marketing voice and carry tracking links; the technical content (endpoints, schemas, examples) is real and documented. By @prime-skills, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/prime-skills-codex-pet
- Fiche en français: https://theskillharbor.com/fr/products/prime-skills-codex-pet
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/prime-skills/runcomfy-agent-skills/blob/main/codex-pet/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

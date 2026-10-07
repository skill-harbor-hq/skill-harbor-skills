<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: fal-ai-community-skills-fal-redesign
description: "Screenshot a coded site, have a vision model write an edit prompt, render the redesigned reference..."
---

# Fal redesign — award-tier design passes for coded websites

💳 **Paid API required** — Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @fal-ai-community's redesign pipeline for coded websites. Hand it a local HTML file or a dev-server URL and the bundled Node runtime runs four modes — `upgrade` (puppeteer screenshot → an opus-class vision model drafts the edit prompt → `fal-ai/gpt-image-2/edit` renders the redesigned reference image → a Markdown build-spec with a "Hard constraints" section plus a `tokens.json` that the agent applies to the real HTML), `describe` (re-run a build-spec on an existing image), `iterate` (screenshot the implemented site and emit a delta-spec vs the reference), and `generate` (freeform brief → mockup → single-file HTML, with parallel design variants and a comparison gallery). Honest caveats: the fal.ai API is metered — a `FAL_KEY` is required and each pass takes 60–180 seconds; the runtime needs `npm install` inside its `runtime/` folder first. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/fal-ai-community-skills-fal-redesign
- Fiche en français: https://theskillharbor.com/fr/products/fal-ai-community-skills-fal-redesign
- Category: Design
- Price: Free
- Verification: unverified
- Source repo: https://github.com/fal-ai-community/skills/blob/main/skills/fal-redesign/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

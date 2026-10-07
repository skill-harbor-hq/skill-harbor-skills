<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: zenstory-ai-oh-story-claudecode-story-cover
description: "Generate professional Chinese web-novel covers from title and pen name, with genre-aware fonts and..."
---

# Chinese web-novel cover generator (GPT-Image-2)

Curated by Skill Harbor — 💳 **Paid API required / API payante requise**: @zenstory-ai's novel-cover studio: from a book title and pen name it detects the genre (xianxia, xuanhuan, ancient/modern romance, urban, suspense, sci-fi, history, horror, light novel), builds a three-layer English image prompt (text layer with genre-specific font styling for the title and a carefully designed author byline, platform style layer, scene layer with 2–3 composition variants), then generates with GPT-Image-2 — either through Codex CLI's built-in image tool (counts toward Codex usage, no key needed) or an API fallback with `GPT_IMAGE_API_KEY` (base64-to-PNG save, versioned outputs, prompt copies kept), with platform export sizing (e.g. 600×800 for Tomato novels via ImageMagick/sips center-crop, no distortion), and a quality-check + iteration loop. Honest caveats: **the skill is written in Chinese**; image generation is paid with no free tier (Codex subscription usage on the built-in path, or your own paid API key on the fallback path — the skill refuses to silently switch to a billable API); prompt text is authored in English, titles rendered in Chinese; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/zenstory-ai-oh-story-claudecode-story-cover
- Fiche en français: https://theskillharbor.com/fr/products/zenstory-ai-oh-story-claudecode-story-cover
- Category: Design
- Price: Free
- Verification: unverified
- Source repo: https://github.com/zenstory-ai/oh-story-claudecode/blob/main/skills/story-cover/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

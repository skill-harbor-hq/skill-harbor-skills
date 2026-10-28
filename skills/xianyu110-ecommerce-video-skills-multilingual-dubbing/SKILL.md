<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: xianyu110-ecommerce-video-skills-multilingual-dubbing
description: "Localise a finished Chinese ecommerce video into other-language versions"
---

# Multilingual Dubbing

Localise a finished Chinese ecommerce product video into other-language versions from the same storyboard.json: the voice-over is rewritten for the target market rather than translated literally (local wording and scenarios, units converted with equivalent values, brand spelling kept, length fitted to each shot at about 2.5 words per second for English) into line_<lang> / sub_<lang> / title_<lang> / cta_<lang> fields plus a top-level tag_<lang>, a matching Microsoft Edge voice is picked per market, and one assemble.py --lang render synthesises each localised line through edge-tts, recomputes shot lengths from the real voice durations, and re-renders the same images, transitions, styled subtitles, title text, ducked BGM and loudness-normalised audio into a finished MP4 + SRT per language, each in its own build folder. Unchanged lines are served from a local cache with no new network call.

- Listing: https://theskillharbor.com/products/xianyu110-ecommerce-video-skills-multilingual-dubbing
- Fiche en français: https://theskillharbor.com/fr/products/xianyu110-ecommerce-video-skills-multilingual-dubbing
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/xianyu110/ecommerce-video-skills

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

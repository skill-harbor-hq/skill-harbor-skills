<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: heygen-com-hyperframes-embedded-captions
description: "Add verbatim, cinematic or VFX-themed captions to a single-subject talking-head video, compositing..."
---

# Embedded captions: cinematic talking-head subtitles burned into the scene

Curated by Skill Harbor — @heygen-com's HyperFrames embedded-captions skill: a full local pipeline that adds captions to an existing single-subject talking-head video without touching the footage. One catalog, picked up front (35 identities); three modes — Standard (verbatim lower-third rail + embed climax composited behind the subject at the peak), Cinematic (pure embed, hero typography composited into the scene), Theme (five themed constitutions: ordnance, terminal, neonsign, stardust, stomp). Everything runs locally end to end: WhisperX transcription via uvx, subject matting, safe-zone computation, frame-accurate preview sheets before the paid render, hard decision gates (refuses multi-speaker, caption-less, garbled or already-captioned clips), and non-negotiables (face never 100% covered, captions stay on-frame, ≥0.5s per caption, timing within 80ms). Needs Node, FFmpeg, Sharp, Puppeteer and GSAP; matting weights download once (~168 MB). Honest caveats: a large render costs minutes — visual QA on the preview sheet is mandatory before rendering; model quality varies with non-native speech; matte quality on busy handheld footage can flicker, so trim and probe first. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/heygen-com-hyperframes-embedded-captions
- Fiche en français: https://theskillharbor.com/fr/products/heygen-com-hyperframes-embedded-captions
- Category: Video
- Price: Free
- Verification: unverified
- Source repo: https://github.com/heygen-com/hyperframes/blob/main/skills/embedded-captions/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

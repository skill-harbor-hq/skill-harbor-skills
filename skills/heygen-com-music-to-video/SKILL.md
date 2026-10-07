<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: heygen-com-music-to-video
description: "Turn your music track into a beat-synced lyric video, slideshow, or kinetic promo."
---

# Music-to-Video Skill for Muse

Turn one music track into a complete beat-synced video — lyric video, slideshow, or kinetic promo. It runs an agentic workflow with user checkpoints: analyze the track with a single local beat analyzer (`analyze-beatgrid.py`), cut it into frames at real musical changes, approve a storyboard, build each frame as a web composition with one worker per frame, then assemble and render the final MP4. No assets required — typography and templates carry a complete video; any images or videos you supply get cut onto the same beat grid. Discovered via skills.sh. Honest note: the heavy lifting (beat analysis, rendering) runs locally and free — but audio track *generation* routes through media providers that may need sign-in; and the skill assumes the HyperFrames ecosystem (CLI + companion skills) around it. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/heygen-com-music-to-video
- Fiche en français: https://theskillharbor.com/fr/products/heygen-com-music-to-video
- Category: Creativity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/heygen-com/hyperframes/blob/main/skills/music-to-video/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

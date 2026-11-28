<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kajisho5-ffmpeg-skill-ffmpeg-skill
description: "Curated by Skill Harbor: Edit video and audio locally with FFmpeg, cut, join, silence, captions..."
---

# FFmpeg Skill

Curated by Skill Harbor: Edit video and audio locally with FFmpeg, with 41 tools for cutting, joining, silence removal, captions, reframing, speed, sync, loudness and platform exports. It runs entirely on your machine, with no cloud, no API keys and no cost, using FFmpeg 6.1 or newer and Python 3.10 or newer.

The workflow starts from a probe of the real file, plans with --dry-run, then chains colour, cut, join, silence, fit, captions, sync, audio, loudness and export, checks the result against the platform asked for, and verifies it from measured numbers, never overwriting a source. Honest limits: transcription needs an engine that already exists and the skill never invents dialogue; highlights rank by loudness, not meaning; sync confidence under 0.3 is suspect; re-encodes drop alpha unless --keep-alpha is passed; captions must come after cropping or they land off-frame; and a missing font for the script fails the job. It executes an edit, it does not decide one. By @kajisho5, listed here with credit to its creator. Discovered via GitHub. Skill Harbor never reviews the code, review it yourself before use.

Updated November 28, 2026: the skill now counts 41 tools: crop.py folded into fit.py, so an exact-box crop is `fit.py in.mp4 --rect 1080:1920:100:0` (crop.py stays as an alias running the same code). One ordinary edit is one call, and new rows cover named audio tracks, J-cuts and L-cuts, fades, mute and Matroska audio.

- Listing: https://theskillharbor.com/products/kajisho5-ffmpeg-skill-ffmpeg-skill
- Fiche en français: https://theskillharbor.com/fr/products/kajisho5-ffmpeg-skill-ffmpeg-skill
- Category: Video
- Price: Free
- Verification: unverified
- Source repo: https://github.com/kajisho5/ffmpeg-skill

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

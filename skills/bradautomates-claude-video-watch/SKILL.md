<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bradautomates-claude-video-watch
description: "Download a video with yt-dlp, extract timestamped frames and a transcript — or let Google's Gemini..."
---

# Watch — ask questions about any video

Curated by Skill Harbor — a video-watching skill by @bradautomates that lets an agent answer questions about any video. With the local engine it downloads the video (URL or local file) with yt-dlp, extracts auto-scaled timestamped frames with ffmpeg and a transcript from captions (or a local WhisperX / Groq / OpenAI fallback), then combines visuals and transcript as evidence. With a Gemini API key, Google's agentic video model watches the full video directly and the report relays its timestamped answer. Includes a guided first-run setup (engine choice, detail levels from transcript-only to token-burner, transcription backend), and security-conscious defaults: keys live in a local `~/.config/watch/.env` (0600 permissions), are never printed, and video content is treated as untrusted evidence, never instructions. Honest caveats: the Gemini engine sends the video to Google (local files are uploaded, then deleted after the answer); the local WhisperX path needs a one-time ~1.5 GB model download and 8 GB RAM; long clips get sparse frame coverage unless you focus a time interval. Credit to its creator. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/bradautomates-claude-video-watch
- Fiche en français: https://theskillharbor.com/fr/products/bradautomates-claude-video-watch
- Category: Video
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bradautomates/claude-video/blob/main/skills/watch/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: volcengine-mediakit-cli-byted-mediakit-editing
description: "Drive a 23-tool video and audio editing CLI — trim, concat, speed, volume, filters, transitions..."
---

# Video/audio editing via mediakit-cli: 23 editing tools, local and cloud

Curated by Skill Harbor — @volcengine's MediaKit editing skill: the agent-facing playbook for 23 editing-domain tools over the `mediakit-cli` binary (v0.2.1, shell permission). Covers timeline trimming and splicing, audio/video speed and volume, filters (spring/sunset/vivid and more), camera-motion effects, transitions, crop/rotate/flip, image overlay, burned-in subtitles, GIF/WebP extraction, fade in/out, audio extraction and muxing, mixing, text-to-scrolling-video (fixed 9:16), image-to-video, and spatial stitching — each with its Cloud/Local support mode, command and reference doc. Includes hard rules (read the shared skill first, only use listed editing tools, never fabricate parameters, set MEDIAKIT_SURFACE=skill and MEDIAKIT_RUNTIME), clarification routing (pure image enhancement, video understanding, OCR and audio-only tasks route to other domains), and per-tool capability boundaries. Honest caveats: the skill text is written in Chinese; Cloud-mode tools require a configured mediakit-cli with auth (check the shared skill's preflight checks first); the machine contract is the live CLI `--schema`, so verify parameters against your installed version before a big batch job. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/volcengine-mediakit-cli-byted-mediakit-editing
- Fiche en français: https://theskillharbor.com/fr/products/volcengine-mediakit-cli-byted-mediakit-editing
- Category: Video
- Price: Free
- Verification: unverified
- Source repo: https://github.com/volcengine/mediakit-cli/blob/main/skills/byted-mediakit-editing/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

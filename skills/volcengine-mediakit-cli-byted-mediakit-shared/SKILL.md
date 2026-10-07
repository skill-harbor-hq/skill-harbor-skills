<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: volcengine-mediakit-cli-byted-mediakit-shared
description: "Route video editing, audio, image, and AI video work to the right mediakit-cli domain skill — edit..."
---

# MediaKit shared hub — professional media-processing entry point

Curated by Skill Harbor — the shared entry skill by @volcengine (ByteDance's Volcengine) for MediaKit, a professional audio/video/image toolkit driven by `mediakit-cli`. It acts as a router: when the user states a media goal, it picks the right domain skill (editing, audio, image, video) before any parameter details are read. Covers install and availability checks, the environment-injection rule (`MEDIAKIT_SURFACE=skill`, `MEDIAKIT_RUNTIME=<host>`) on every real business call, command discovery via `--help`/`--schema`, Cloud vs Local modes (per-command override, async `query-task` protocol for cloud jobs), and a broad capability map — video cutting/assembly/transitions/filters/mixing, speech-to-subtitle, subtitle erase, watermark handling, quality enhancement and detection, voice/background separation, keying and face swap, OCR, smart crop. Honest caveats: the skill is written in Chinese; some tools run in Cloud mode on Volcengine infrastructure (an account may be needed) while others support Local mode — the skill tells you to read each tool's reference before trusting a parameter; face-swap capabilities deserve a thought about consent before use. Credit to its creator. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/volcengine-mediakit-cli-byted-mediakit-shared
- Fiche en français: https://theskillharbor.com/fr/products/volcengine-mediakit-cli-byted-mediakit-shared
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/volcengine/mediakit-cli/blob/main/skills/byted-mediakit-shared/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

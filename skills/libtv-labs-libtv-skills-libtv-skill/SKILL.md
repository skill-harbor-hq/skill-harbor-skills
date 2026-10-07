<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: libtv-labs-libtv-skills-libtv-skill
description: "Create sessions, send natural-language prompts (text-to-image, text-to-video, edits), upload..."
---

# LibTV image & video creation: AI generation and editing via the LibTV platform

💳 **Paid API required** — the skill drives the LibTV platform and requires a `LIBTV_ACCESS_KEY` (paid image/video generation service). Curated by Skill Harbor — @libtv-labs' agent-im skill for creating and editing images and videos through the LibTV (LiblibAI) platform: text-to-image, text-to-video, image-to-video, video continuation, local edits, element replacement, style transfer, video replication, plus complex creations like one-sentence short dramas (script → storyboard → finished piece), music MVs, product ad films, storyboard design and educational videos, powered by models such as Seedance 2.0, Kling 3.0/O3, Wan 2.6, NanoBanana, Midjourney and Seedream 5.0. The agent acts as a courier: upload reference files to OSS, pass the user's raw description verbatim to the session, poll progress, auto-download results, and present result links plus the project canvas link — it must never rewrite, expand or self-decompose the user's prompt (the backend agent is the specialist). Five operations via stdlib-only Python scripts: create_session/send message, query session progress (8-second incremental polling, 3-minute timeout), switch project, upload files (200MB max), batch-download results. Honest caveats: **the skill is written in Chinese**; complex generations (short dramas, MVs) take a long time — budget patience. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/libtv-labs-libtv-skills-libtv-skill
- Fiche en français: https://theskillharbor.com/fr/products/libtv-labs-libtv-skills-libtv-skill
- Category: Photo & Video
- Price: Free
- Verification: unverified
- Source repo: https://github.com/libtv-labs/libtv-skills/blob/main/skills/libtv-skill/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

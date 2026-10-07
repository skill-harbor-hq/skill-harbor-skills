<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: wecomteam-wecom-cli-wecomcli-message
description: "Send messages to WeCom chats (text, Markdown, image, file, AMR voice, video) with strict..."
---

# WeCom messaging: send text, Markdown, images, files, voice and video via wecom-cli

Curated by Skill Harbor — @wecomteam's skill for sending messages through WeCom (the enterprise WeChat chat service) via the `wecom-cli` command line. The skill first scopes the current sendable chat range (the authorized user, or recent DMs and group chats with prior message history), then sends text/Markdown (up to 20480 UTF-8 bytes), images, files, AMR-format voice messages, and video (with optional title/description) — with strict targeting guardrails: the chat_id must be copied verbatim from a fresh `sessions list` call (never a user-typed ID, a stored ID, or one derived from a name), ambiguous targets must be confirmed with the user, and internal IDs are never shown to the user. It also covers media upload via the companion `wecomcli-media` skill. Honest caveats: **the skill is written in Chinese**; requires the `wecom-cli` binary installed and a WeCom account; depends on the `wecomcli-shared` prerequisite skill (not included here); WeCom is primarily a China-market product. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/wecomteam-wecom-cli-wecomcli-message
- Fiche en français: https://theskillharbor.com/fr/products/wecomteam-wecom-cli-wecomcli-message
- Category: Communication
- Price: Free
- Verification: unverified
- Source repo: https://github.com/wecomteam/wecom-cli/blob/main/skills/wecomcli-message/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

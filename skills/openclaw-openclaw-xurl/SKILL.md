<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: openclaw-openclaw-xurl
description: "⚠️ AUTHORIZED USE ONLY — Drive the official xurl CLI from your agent — shortcut commands for..."
---

# xurl CLI for X (Twitter) API: posts, replies, DMs, media and raw v2 calls (short listing)

⚠️ AUTHORIZED USE ONLY — this skill can perform real actions on your X account; never use it without the account owner's explicit approval for each action. Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @openclaw's skill for driving the `xurl` CLI (X's official CLI) from an agent. Shortcut commands return JSON; raw mode covers any v2 endpoint. Covers auth (tokens live in `~/.xurl` — check with `xurl auth status` rather than reading the file, pass secrets through the prompt not inline so they stay out of shell history, note `--verbose` prints auth headers into tool output), common shortcuts (post, reply, quote, delete, read, search, whoami, user lookup, timeline, mentions, like/unlike, repost/unrepost, bookmark, follow/unfollow, block/mute, DM send and list), media (upload image/video, poll `media status`, post with `--media-id`), auth and app management, per-request app/auth overrides, raw API calls (keep complex payloads in temp files), and output/error semantics (non-zero exit on API/auth/network errors, 401/403 auth-scope guidance, 429 backoff). Honest caveats: the agent can publish real posts, replies and DMs under your X account — review every send yourself; X API access tiers and their costs apply (check your X developer plan); install via brew (`xdevplatform/tap/xurl`) or npm (`@xdevplatform/xurl`) is a prerequisite; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor...

- Listing: https://theskillharbor.com/products/openclaw-openclaw-xurl
- Fiche en français: https://theskillharbor.com/fr/products/openclaw-openclaw-xurl
- Category: Social
- Price: Free
- Verification: unverified
- Source repo: https://github.com/openclaw/openclaw/blob/main/skills/xurl/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

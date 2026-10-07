<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: abgne-line-dev-messaging-api
description: "Full LINE Messaging API reference: webhook setup and signature verification..."
---

# LINE Messaging API — build, review, and debug LINE bots

Curated by Skill Harbor — @abgne's messaging-api skill, listed here with credit to its creator: a comprehensive, battle-ready reference for building, reviewing, and debugging LINE Bots on the LINE Messaging API. It walks the agent through a build workflow (load the right reference file per feature, consult expert profiles for architecture choices, code to the specs) and a review/debug workflow (cross-check code against size limits, token expiry, counting rules, required fields). Covered in depth: webhook signature verification (HMAC-SHA256, never reformat the body before verifying), reply/push/multicast/narrowcast/broadcast sending with rate limits and retry policy, the three-layer Flex Message structure (containers/blocks/components) with a component catalog, Rich Menu CRUD and display priority, audience management, messaging insights, coupons, channel access token lifecycle, URL schemes, and group/room APIs. The skill's own iron rule: never answer LINE API questions from memory — always consult the references, because LINE updates its APIs frequently. Honest caveats: needs a LINE Developers channel and its access token/channel secret (free, but your credentials live in your own vault); LINE's API changes often — the reference files are the source of truth, not the agent's memory; push quotas apply per plan. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/abgne-line-dev-messaging-api
- Fiche en français: https://theskillharbor.com/fr/products/abgne-line-dev-messaging-api
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/abgne/line-dev/blob/main/skills/messaging-api/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

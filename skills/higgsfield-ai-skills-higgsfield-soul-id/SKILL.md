<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: higgsfield-ai-skills-higgsfield-soul-id
description: "Train a reusable Soul character on a person's face for identity-faithful image and video generation"
---

# Higgsfield Soul ID: train a face-faithful identity model

💳 **Paid API required** — training a Soul character requires a Higgsfield paid plan (Basic+); the free plan cannot submit training. Curated by Skill Harbor — ⚠️ **Security warning** — the skill's bootstrap instructs installing the `higgsfield` CLI via `curl … | sh`; prefer the official installer or a package manager instead. @higgsfield-ai's Soul ID workflow for agents: bootstrap the CLI and authenticate (`higgsfield auth login`), collect 5–20 varied face photos under one name, pick an image or cinematic variant, submit training (`higgsfield soul-id create --name … --image …`), poll silently until the reference id is ready, then reuse that id with `higgsfield-generate` (`--soul-id <id>`) on soul-capable models (`text2image_soul_v2`, `soul_cinematic`) for identity-consistent images and video, plus list/get commands for existing Souls and photo-guide and troubleshooting references. Honest caveats: this is NOT a one-shot face swap — that is a different command; training takes minutes and photo quality drives results; CLI flags stay English while the agent answers in the user's language; listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/higgsfield-ai-skills-higgsfield-soul-id
- Fiche en français: https://theskillharbor.com/fr/products/higgsfield-ai-skills-higgsfield-soul-id
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/higgsfield-ai/skills/blob/main/higgsfield-soul-id/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

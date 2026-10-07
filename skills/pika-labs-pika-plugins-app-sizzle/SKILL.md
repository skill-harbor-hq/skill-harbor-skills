<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pika-labs-pika-plugins-app-sizzle
description: "Generate a 15-second cinematic app teaser from real App Store screenshots — GPT-image-2..."
---

# App Sizzle: cinematic 1080p iOS app teaser videos from real screenshots

💳 **Paid API required** — every run burns roughly 3,000-4,000 Pika credits (~$30-$40); the skill gates on an explicit `proceed` reply (or `cost_ack=proceed` in config) before any paid MCP call. Curated by Skill Harbor — @pika-labs's app-sizzle skill: generate a polished 15-second 1080p cinematic teaser for an iOS app from real app screens. The workflow is asset-grounded by design: Stage 0 sources real screens (Pika MCP App Store fetch, live website auto-capture, or user-supplied files) and the brand logo — no invented UI, placeholders are rejected; Stage 1 analyzes every screenshot into a feature map (UI shown, feature represented, emotional register: hook/build/reveal) with visual-contrast scoring between screens; Stage 2 designs the 4-beat narrative arc (Hook 0-3s, Build 3-10s, Reveal 10-13s, Logo 13-15s) from arc types (Problem→Solution, Feature Parade, Journey, Transformation); Stage 2.5 enhances each screen with GPT-image-2 (short non-descriptive prompt, parallel calls); Stage 3 writes the Seedance prompt from the feature map and arc (never from imagination) with two templates — Cinematic Narrative or Liquid Glass (photo/camera apps only) — and specific camera vocabulary (extreme macro close-up, crash zoom, whip pan, orbital sweep, push-in drift, pull-back to reveal); generation runs at 1080p with sound via Seedance, Kling as fallback on moderation/balance/timeout failures; Stage 4 adds a deterministic COMING SOON text overlay (never rendered by the video model)...

- Listing: https://theskillharbor.com/products/pika-labs-pika-plugins-app-sizzle
- Fiche en français: https://theskillharbor.com/fr/products/pika-labs-pika-plugins-app-sizzle
- Category: Marketing
- Price: Free
- Verification: unverified
- Source repo: https://github.com/pika-labs/pika-plugins/blob/main/skills/app-sizzle/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

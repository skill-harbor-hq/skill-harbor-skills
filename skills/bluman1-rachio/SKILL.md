<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-rachio
description: "Water your lawn from Muse — zones, schedules, and real valves, confirmed before every watering run."
---

# Rachio Irrigation Connector for Muse

A Muse agent skill that controls Rachio smart sprinkler controllers through Rachio's public API: zones, schedules, watering history, and manual zone runs. Rachio's API is free (roughly 1,700 requests/day) — no paid tier needed for normal use. Opening a valve waters a real lawn with real water, so the skill confirms with the user before every watering run: which zones, how long. Reads (schedules, history, device info) are safe anytime. Uses a Rachio API key, kept in Muse's secure vault. Draft: written from Rachio's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-rachio
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-rachio
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/rachio

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

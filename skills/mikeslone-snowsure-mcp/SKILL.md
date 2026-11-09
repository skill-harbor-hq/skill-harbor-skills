<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mikeslone-snowsure-mcp
description: "Live snow, lifts and forecasts for 500+ ski resorts."
---

# Snowsure Ski Reports for Muse

Snowsure gives Muse live snow data for 500+ ski resorts: current conditions, snowfall, lift status, 7-day forecasts and passes. The skill always fetches fresh data and never answers from memory. Ask about Mont Tremblant, Whistler or any other resort, and Muse checks snowsure.ai on the spot.

Live test, 2026-11-08, from the test PC: server answers in 0.2–3.5 s. Mont Tremblant resolved to `mont-tremblant-resort`, live answer « air 0°C, closed — opens Nov 26, 2026 », and a snow report returned 29 fresh figures in cm. Real data, not recalled text.

Caveats:
- The skill depends entirely on the snowsure.ai server — if it is down, the skill is useless.
- Your question (resort, dates, what you want to know) goes to snowsure.ai on every ski question. No account, no key, no personal data unless you put it in the question.
- The SKILL.md says 39 tools; the server exposes 48 today.
- The `claude mcp add` command itself was not tested (no Claude Code on the test PC — the MCP connection was exercised directly, same endpoint). The REST path and the pass / avalanche / road-trip tools were not tested.

- Listing: https://theskillharbor.com/products/mikeslone-snowsure-mcp
- Fiche en français: https://theskillharbor.com/fr/products/mikeslone-snowsure-mcp
- Category: Outdoors
- Price: Free
- Verification: verified
- Source repo: https://github.com/mikeslone/snowsure-mcp

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

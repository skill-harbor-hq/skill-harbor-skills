<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: nausika-app-passage-planning
description: "Plan sea passages with real marine data — routing, wind, waves, tides, anchorages"
---

# Nausika Sailing Passage Planning Skill for Muse

Turns Muse into a disciplined sailing-passage planner driven by real marine data through the Nausika MCP tools: it geocodes every place name first (never coordinates from memory), pulls marine forecasts at origin, destination, and turning waypoints with forecast-horizon presets (now / today / tactical 3-day / planning 8-day / extended 14-day), computes sea distances by routing around land (Mediterranean sea-lane graph), finds marinas, anchorages, and shelter along the route with depth, holding, exposure, and ratings, quotes tides honestly (across most of the Mediterranean the range is under 0.3 m — negligible, and the skill says so instead of dressing it up), and delivers a leg-by-leg passage plan table (bearing, distance in nautical miles, ETA at boat speed, wind/sea, shelter) ending with the weather window, a go/no-go call, and fallback ports. Discovered via skills.sh. Honest note: the skill is only the workflow — it needs the Nausika MCP server connected to the agent (install the nausika-setup skill or the Nausika plugin first; without it the skill refuses to improvise a substitute); sea routing covers the Mediterranean basin only, while forecasts, tides, and geocoding are worldwide; and Nausika is data, not advice — it does not replace charts, pilot books, or notices to mariners, and the skipper decides. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/nausika-app-passage-planning
- Fiche en français: https://theskillharbor.com/fr/products/nausika-app-passage-planning
- Category: Boating & Sailing
- Price: Free
- Verification: unverified
- Source repo: https://github.com/nausika-app/nausika-skills/blob/main/nausika-passage-planning/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

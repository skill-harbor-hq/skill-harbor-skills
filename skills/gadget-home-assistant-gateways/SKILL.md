<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gadget-home-assistant-gateways
description: "Read what Home Assistant already knows about your home, and change only allowlisted entities, only..."
---

# Home Assistant Gateways

Curated by Skill Harbor: a gadget skill for homes that already run Home Assistant, typically on a Raspberry Pi or home server, where Home Assistant is the single gateway to everything else. Instead of re-integrating each ecosystem, it reads the one place where climate, lights, presence, covers, media, and sensor states already surface as entities. The discipline starts before any question: confirm the Home Assistant base URL answers on the home network, inventory the entity list, match friendly names and rooms with the user (they rarely match the user's words out of the box), and agree an allowlist, which entities Muse may read, and the much smaller set it may ever act on. Status questions report the value, the room and device it maps to, and when the state last changed, so freshness can be judged; history questions use the history endpoint filtered to the relevant entities instead of guessing trends from a single read. Changes are the exception, not the default: only on explicit request, only for allowlisted entities, one service call per requested change, never extra devices added while at it, and safety-relevant domains (locks, covers, alarm panels, whole-home climate) get a spoken pause restating exactly what will change before anything moves. It never edits the installation itself: no automations, scenes, integrations, dashboards, or configuration changes from a skill session. The token behind it is owner-created and owner-stored, Home Assistant stays local with no...

- Listing: https://theskillharbor.com/products/gadget-home-assistant-gateways
- Fiche en français: https://theskillharbor.com/fr/products/gadget-home-assistant-gateways
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/amanthakkar/musecases/tree/main/skills/gadget-home-assistant-gateways

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

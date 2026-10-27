<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gadget-google-nest-thermostats
description: "Read and adjust Nest thermostats through a local bridge, with every change verified by a fresh read."
---

# Google Nest Thermostats

Curated by Skill Harbor: a gadget skill for homes whose Nest thermostats are already bridged into a local system Muse can reach, most commonly Home Assistant on a Raspberry Pi, through Google's Smart Device Management API. This is not the Google Home app, not Google Cast, and not Matter commissioning: it reads and adjusts through the bridge. For status questions it reports ambient temperature and humidity, HVAC status, mode, and the active setpoint, matched to rooms with the user first, since bridge device names rarely match room names. For a requested change it sets the mode or setpoint through the bridge, then re-reads the device after a short wait to confirm the change actually applied, because Smart Device Management writes can lag and occasionally report success before the thermostat applies them. The setup behind it is real work the owner does once: a Google Device Access project with a one-time US$5 registration fee, an OAuth consent flow completed by the account owner, and tokens that stay in the bridge, re-consented only by the owner if they expire. The skill draws firm lines: no changes to the Device Access project, OAuth grants, account sharing, or thermostat schedules and learning features from a skill session, comfort control only, never presented as freeze, heat-safety, or occupancy protection, and temperature history is household data, reported only as asked. By @amanthakkar, listed here with credit to its creator. Skill Harbor never reviews the code, review...

- Listing: https://theskillharbor.com/products/gadget-google-nest-thermostats
- Fiche en français: https://theskillharbor.com/fr/products/gadget-google-nest-thermostats
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/amanthakkar/musecases/tree/main/skills/gadget-google-nest-thermostats

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

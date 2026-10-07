<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: setasoma-mycodo-autonomous-control
description: "Let your Muse run the grow tent: sensors, fans and humidifiers on autopilot"
---

# Mycodo Autonomous Mushroom Control

Curated by Skill Harbor — turns your Muse into the operator of a mushroom grow tent: a phase-aware decision engine reads temperature, humidity and CO2 sensors via Mycodo on a Raspberry Pi, evaluates readings against species-specific YAML thresholds (lion's mane, oyster, shiitake, reishi, turkey tail, maitake), and fires fan and humidifier relays through colonization, primordia, fruiting and rest phases — with safety guards against oversaturation, a 10-minute follow-up checker that verifies actuator effects, operator overrides, and HTML reports with camera snapshots. Discovered via skills.sh, listed here with credit to its creator by @setasoma. Honest caveats: serious hardware is required (Raspberry Pi running Mycodo + InfluxDB, SHT45 and SCD41 sensors, relay-controlled fan and humidifier, Hermes agent framework with cron); the skill's own documentation records production incidents (a dry-run that silently fired nothing for days, humidity climbing to 99.91% unchecked) — review the safety guards carefully before letting it touch real relays; the contamination-check feature is dormant (standby, no model configured); 1 install on the catalog, but popularity is not a review. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/setasoma-mycodo-autonomous-control
- Fiche en français: https://theskillharbor.com/fr/products/setasoma-mycodo-autonomous-control
- Category: DIY & Hobbies
- Price: Free
- Verification: unverified
- Source repo: https://github.com/setasoma/mycodo-hermes-skill

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

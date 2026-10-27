<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gadget-tesla
description: "Charge, drives, efficiency, and vampire drain from a self-hosted TeslaMate stack, read-only by..."
---

# Tesla

Curated by Skill Harbor: a gadget skill for homes that run, or want to run, a self-hosted Tesla data stack, typically TeslaMate on a Raspberry Pi or home server, optionally with Tesla's Fleet Telemetry server feeding a local MQTT broker and analytics store. It answers from local data first: current state (charge level, plugged in, asleep) from TeslaMate, drives and charges from its database, and fine-grained telemetry where the stack has it, cross-checking headline numbers against a second local source and stating the source and observation time for every number, since the layers update on different cadences. From that data it computes per-drive energy use against the vehicle's EPA rating, the self-driving share of a drive from the telemetry counter, vampire drain measured only across parked, unplugged, asleep periods and labeled as an estimate, and charging sessions with start and end, charge gained, energy added, and whether the session overlapped the household's peak pricing window. The setup behind it is the owner's work: a Tesla developer account and Fleet API app with a virtual key enrolled on the car, TeslaMate in its sleep-friendly configuration, and optionally fleet telemetry, with Tesla including a monthly free credit (currently $10) and typical reads costing fractions of a cent beyond it. The limits are the point: read-only by default, vehicle commands only on explicit request through an owner-controlled command proxy already deployed, never Fleet API commands...

- Listing: https://theskillharbor.com/products/gadget-tesla
- Fiche en français: https://theskillharbor.com/fr/products/gadget-tesla
- Category: Automotive
- Price: Free
- Verification: unverified
- Source repo: https://github.com/amanthakkar/musecases/tree/main/skills/gadget-tesla

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

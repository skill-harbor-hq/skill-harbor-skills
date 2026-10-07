<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-calcom
description: "List bookings and event types, create bookings."
---

# Cal.com Connector for Muse

A Muse agent skill that reads and writes your Cal.com scheduling: list bookings (filterable by status), list event types, and create bookings. Creating a booking is a write — the skill confirms the event type, time, and attendee first, and always confirms the timezone. Uses a personal Cal.com API key (keys start with `cal_` or `cal_live_`), kept in Muse's secure vault. Draft: written from Cal.com's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-calcom
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-calcom
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/calcom

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

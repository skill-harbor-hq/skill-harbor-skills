<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-reschedule-meeting
description: "Move a Calendar event to a new time and notify all attendees"
---

# 💳 Reschedule Meeting (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that finds a Calendar event, patches its start and end times, and notifies every attendee automatically (`sendUpdates: all`). Distinct from the sibling recipe create-events-from-sheet: that one bulk-creates events from spreadsheet rows; this one moves a single existing meeting. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-calendar utility skill is loaded and the gws binary is installed and authenticated; you need the event ID and the new times in ISO format with a timezone — double-check the timezone or you'll move the meeting to the wrong hour. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-reschedule-meeting
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-reschedule-meeting
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-reschedule-meeting/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

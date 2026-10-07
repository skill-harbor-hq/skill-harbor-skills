<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-create-events-from-sheet
description: "Bulk-create Calendar events from spreadsheet rows"
---

# 💳 Sheet to Calendar Events (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that reads event data from a Sheet range and creates one Google Calendar event per row (`gws calendar +insert` with summary, times and attendees). Distinct from the sibling recipe reschedule-meeting: that one moves a single existing event; this one creates many new ones. Also distinct from the sibling post-mortem-setup: that one builds a whole incident workflow (Doc + meeting + Chat announcement); this one is purely bulk event creation. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-sheets and gws-calendar utility skills are loaded and the gws binary is installed and authenticated; the Sheet columns must map cleanly to event fields — sanitize the data first or you'll create dozens of wrong events, and deleting them is manual. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-create-events-from-sheet
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-create-events-from-sheet
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-create-events-from-sheet/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

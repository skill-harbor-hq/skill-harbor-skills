<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-sync-contacts-to-sheet
description: "Export the Workspace directory contacts into a spreadsheet"
---

# 💳 Contacts to Sheet (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that lists the Google Workspace directory contacts (`gws people people listDirectoryPeople` with names, emails and phone numbers) and appends them row by row into a Google Sheet. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-people and gws-sheets utility skills are loaded and the gws binary is installed and authenticated; the directory source only returns domain profiles (not personal contacts), the API pages at 100 entries so large organizations need pagination, and exporting colleague data raises privacy considerations — use it for legitimate internal purposes only. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-sync-contacts-to-sheet
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-sync-contacts-to-sheet
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-sync-contacts-to-sheet/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

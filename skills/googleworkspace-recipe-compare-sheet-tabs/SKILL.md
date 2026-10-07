<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-compare-sheet-tabs
description: "Diff two tabs of a Google Sheet and report the differences"
---

# 💳 Compare Sheet Tabs (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that reads two tabs of the same spreadsheet (`gws sheets +read` with explicit ranges like "January!A1:D" vs "February!A1:D") and compares the data to identify changes. Distinct from the sibling recipe googleworkspace-recipe-generate-report-from-sheet: that one turns Sheet data into a formatted report document; this one is purely about diffing two tabs. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-sheets utility skill is loaded, the gws binary is installed and authenticated, and comparison logic is left to the agent — the recipe reads the data, it doesn't do semantic diffing for you. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-compare-sheet-tabs
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-compare-sheet-tabs
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-compare-sheet-tabs/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

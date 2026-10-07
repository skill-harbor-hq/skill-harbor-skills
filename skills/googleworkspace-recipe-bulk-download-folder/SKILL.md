<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-bulk-download-folder
description: "List every file in a Drive folder and download them all, exporting Docs to PDF"
---

# 💳 Bulk Download Drive Folder (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that lists all files in a Google Drive folder, downloads each one, and exports Google Docs as PDF (`gws drive files list`, `files get`, `files export`). Distinct from the sibling recipe backup-sheet-as-csv (lot 31): that one backs up a single spreadsheet as CSV; this one pulls down an entire folder's contents. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-drive utility skill is loaded and the gws binary is installed and authenticated; very large folders will take a long time and hit Drive API quotas — iterate in pages and mind the rate limits. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-bulk-download-folder
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-bulk-download-folder
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-bulk-download-folder/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

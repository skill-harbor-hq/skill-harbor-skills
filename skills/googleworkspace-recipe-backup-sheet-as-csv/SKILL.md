<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-backup-sheet-as-csv
description: "Export a Google Sheet as CSV for local backup or processing"
---

# Recipe: Backup Sheet as CSV

💳 Curated by Skill Harbor — a gws recipe: export a Google Sheets spreadsheet as a CSV file for local backup or downstream processing — either via the Drive export endpoint (mimeType text/csv) or by reading a range directly with the gws sheets reader in csv format. Composes two utility skills (gws-sheets + gws-drive), which must be loaded first. Requires the gws CLI and a paid Google Workspace account — there is no free tier for this CLI. By @googleworkspace, listed here with credit to its creator. Honest caveats: CSV flattens one sheet at a time — multi-tab workbooks need one export per tab; formulas export as values; gws-shared must be read first for auth and global flags. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-backup-sheet-as-csv
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-backup-sheet-as-csv
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-backup-sheet-as-csv/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

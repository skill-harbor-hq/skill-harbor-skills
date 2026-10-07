<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-label-and-archive-emails
description: "Apply a Gmail label to matching messages and archive them out of the inbox"
---

# 💳 Label and Archive Emails (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that searches Gmail for matching messages, applies a label to them (`messages modify` with addLabelIds), and archives them out of the inbox (removeLabelIds INBOX) to keep it clean. Distinct from the sibling recipe create-gmail-filter (lot 31): that one creates a standing Gmail filter rule that applies automatically to future mail; this one is a one-off action you run on messages that already match. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-gmail utility skill is loaded and the gws binary is installed and authenticated; archiving is reversible but batch-applying labels to the wrong search results is easy — verify the query returns what you expect before modifying. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-label-and-archive-emails
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-label-and-archive-emails
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-label-and-archive-emails/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

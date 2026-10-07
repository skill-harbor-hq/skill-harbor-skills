<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-send-team-announcement
description: "Broadcast an announcement via Gmail and a Google Chat space at once"
---

# 💳 Team Announcement (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that sends a team announcement through two channels at once: an email to the team (`gws gmail +send`) and a message in a Google Chat space (`gws chat +send`). Distinct from the sibling recipe share-doc-and-notify: that one shares a document with edit access and emails its link; this one broadcasts a message with no document sharing involved. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-gmail and gws-chat utility skills are loaded and the gws binary is installed and authenticated; you need the Chat space ID and the recipients' addresses — and remember the message goes to both channels, so don't send anything you'd want to keep to one audience. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-send-team-announcement
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-send-team-announcement
- Category: Communication
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-send-team-announcement/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-forward-labeled-emails
description: "Batch-forward every Gmail message carrying a given label to another address"
---

# 💳 Forward Labeled Emails (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that finds all Gmail messages carrying a specific label (`label:needs-review`), fetches each one's content, and forwards it as a new email to another address. Distinct from the already-listed googleworkspace-gws-gmail-forward: that is a single-message forward utility (`+forward` on one message ID with attachments and draft mode); this is a batch workflow that forwards every message under a label. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-gmail utility skill is loaded and the gws binary is installed and authenticated; forwarding happens as new sends from your account — bulk-forwarding a large label will send many emails and may trip Gmail sending limits, and forwarded content leaves your mailbox, so verify the label and recipient first. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-forward-labeled-emails
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-forward-labeled-emails
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-forward-labeled-emails/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

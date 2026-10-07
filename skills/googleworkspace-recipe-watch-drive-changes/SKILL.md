<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-recipe-watch-drive-changes
description: "Subscribe to push notifications on Drive files or folders via Pub/Sub"
---

# 💳 Watch Drive Changes (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a step-by-step recipe that creates a push subscription on a Drive file or folder (`gws events subscriptions create` with a Pub/Sub topic endpoint), lists active subscriptions and renews them before expiry. Distinct from the already-listed googleworkspace-gws-gmail-watch: that utility watches a Gmail mailbox; this recipe subscribes to Google Drive change events — different API, different resource. By @googleworkspace, listed here with credit to its creator. Honest caveats: the recipe assumes the gws-events utility skill is loaded and the gws binary is installed and authenticated; you need a Google Cloud Pub/Sub topic to receive the notifications, and subscriptions expire — the recipe shows renewal but doesn't run a renewal loop for you. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-recipe-watch-drive-changes
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-recipe-watch-drive-changes
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/recipe-watch-drive-changes/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

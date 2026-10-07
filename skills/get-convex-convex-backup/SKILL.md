<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: get-convex-convex-backup
description: "Set up Convex backups — and actually prove the restore works with a restore drill"
---

# Convex Backup & Restore Drill

💳 Curated by Skill Harbor — does both halves of the backup story, because most people only do the first: it sets up regular snapshot exports (`npx convex export`, with `--include-file-storage` when the app stores files) on a schedule matched to how fast the data changes and how much loss is tolerable (RPO), recommending CI/cron to durable storage you control with a retention window. Then it does the half almost nobody does: a RESTORE DRILL that recovers the snapshot into a throwaway preview and asserts the data came back intact — the same primitives as convex-migrate-rehearse (snapshot export → preview deploy → snapshot import), pointed at recovery instead of a forward change. The backup artifact is real sensitive data, treated as such. Honest prerequisites: the drill's restore target is a throwaway preview, which needs a Preview Deploy Key — a paid-tier feature; without it, the skill drills against a fresh personal dev deployment seeded with the snapshot and says so. By @get-convex, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/get-convex-convex-backup
- Fiche en français: https://theskillharbor.com/fr/products/get-convex-convex-backup
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/get-convex/agent-skills/blob/main/skills/convex-backup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

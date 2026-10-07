<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: get-convex-convex-migrate-rehearse
description: "Rehearse a live-app schema change on a snapshot-seeded preview — green there, then promote to prod"
---

# Convex Migration Rehearsal

💳 Curated by Skill Harbor — rehearses a schema change on a throwaway preview before it ever touches prod. A schema push on Convex validates every existing document against the new schema and fails the push if any row doesn't conform — a real data-conformance gate, and the safe move is to let it fail on a rehearsal copy, not on prod. The skill snapshots the prod data (`npx convex export`), creates a preview deployment from the pre-change code, seeds it with the snapshot, pushes the new schema and runs the backfill there, watches the gate, then promotes the proven change to prod with the snapshot as rollback. Honest prerequisites: creating preview deployments needs a Preview Deploy Key, a paid-tier feature; without it the skill rehearses on a personal dev deployment seeded with the snapshot and says so. Distinct from convex-migrate (the migration procedure itself) — this one is the dress rehearsal. By @get-convex, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/get-convex-convex-migrate-rehearse
- Fiche en français: https://theskillharbor.com/fr/products/get-convex-convex-migrate-rehearse
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/get-convex/agent-skills/blob/main/skills/convex-migrate-rehearse/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

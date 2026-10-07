<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-triggerdev
description: "Trigger background jobs, list runs, manage schedules."
---

# trigger.dev Connector for Muse

A Muse agent skill that manages your trigger.dev background jobs: list runs, check a run's status and output, trigger task runs, cancel runs, and list schedules. `trigger` and `cancel` are writes — confirmed with you first. Honest note: triggering a task starts real compute that can cost money. Runs are async — poll the run until it moves to COMPLETED or FAILED. trigger.dev has a free tier. Draft: written from trigger.dev's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-triggerdev
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-triggerdev
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/triggerdev

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-clickup
description: "List ClickUp workspaces and tasks, and create tasks."
---

# ClickUp Connector for Muse

A Muse agent skill that works your ClickUp: list workspaces ("teams"), list tasks in a list, and create tasks. Creating a task is a write — the skill confirms the task name and destination list first; reading needs no confirmation. Uses a personal ClickUp API token (tokens start with `pk_`, sent raw in the Authorization header), kept in Muse's secure vault. Tip: a list's numeric ID is in its ClickUp URL. Draft: written from ClickUp's public API v2 docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-clickup
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-clickup
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/clickup

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

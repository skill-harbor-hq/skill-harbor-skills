<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-ticktick
description: "Read and write TickTick: list projects and tasks, create tasks, complete and delete tasks."
---

# TickTick Connector for Muse

A Muse agent skill that reads and writes your TickTick task lists: list projects, read a project's tasks, create tasks, mark tasks complete, delete tasks. Deleting is destructive and creating is a write — both confirm first, unless standing permission exists; completing a task is low-risk and reversible. Note: this API covers tasks and projects only — no habits, notes, or calendar endpoints. OAuth 2.0 via a free self-serve developer app (developer.ticktick.com), token kept in Muse's secure vault (tokens last ~180 days). TickTick has a free plan. Draft: written from TickTick's public Open API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-ticktick
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-ticktick
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/ticktick

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

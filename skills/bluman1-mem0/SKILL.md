<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-mem0
description: "Persistent memory layer: store, search, and manage memories."
---

# mem0 Connector for Muse

A Muse agent skill that manages your mem0 memory layer: store memories extracted from messages, run semantic search over them, and handle the full lifecycle (list, read, get one, change history, delete) scoped by user, agent, app, or run. Add and search are async — they return an event id you poll until success; never invent memory contents before the poll succeeds. Honest note: mem0 v3 add is add-only (it does not auto-update or auto-delete older conflicting memories), so search first when a fact may already exist. `wipe` deletes every memory in the scope — always confirmed. The free Hobby tier covers 10k add requests + 1k retrieval requests per month. Draft: written from mem0's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-mem0
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-mem0
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/mem0

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-zep
description: "Temporal knowledge-graph memory: threads, facts, conversation history."
---

# Zep Connector for Muse

A Muse agent skill that uses Zep as temporal knowledge-graph memory: create user containers and threads, append conversation messages (Zep extracts facts and entities asynchronously), read the distilled facts for a thread, and read message history. Writes need your confirmation; reads need none. Honest notes: fact extraction is async — allow a few minutes before new facts appear; Zep is metered on ingestion credits (~10k credits/month free, paid plans from ~$49/mo), so warn before bulk ingestion. Draft: written from Zep's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-zep
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-zep
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/zep

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

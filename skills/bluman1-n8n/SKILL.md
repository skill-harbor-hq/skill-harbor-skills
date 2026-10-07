<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-n8n
description: "Read and write n8n workflows; updates are destructive and always confirmed."
---

# n8n Connector for Muse

A Muse agent skill that reads and writes your n8n workflows through the public REST API: list and inspect workflows, create and update them, list executions. Updating is destructive (PUT replaces the whole workflow) — the skill GETs the current workflow first and confirms every change with you. There is no execute-by-ID: runs go through webhook triggers. Uses an n8n API key plus your instance host (cloud or self-hosted), kept in Muse's secure vault. Honest note: the public REST API is unavailable on n8n Cloud free trials — Starter plan or higher, or self-hosted. Draft: written from n8n's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-n8n
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-n8n
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/n8n

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

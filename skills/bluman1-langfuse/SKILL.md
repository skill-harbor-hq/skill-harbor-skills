<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-langfuse
description: "Query LLM traces and observations; manage prompts and scores."
---

# Langfuse Connector for Muse

A Muse agent skill for Langfuse LLM observability: browse traces and observations, list prompts and datasets, score traces, and add dataset items. Reading needs no confirmation; scoring a trace and adding dataset items are writes — the skill confirms first. Works against Langfuse Cloud (EU or US) or your self-hosted instance (declare the host at connect time). Honest note: ingested data can lag ~15–30 seconds behind a run — a missing trace may just need a moment. Langfuse has a free cloud tier. Draft: written from Langfuse's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-langfuse
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-langfuse
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/langfuse

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

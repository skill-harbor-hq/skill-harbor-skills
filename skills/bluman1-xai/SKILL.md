<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-xai
description: "Query Grok chat completions and list available Grok models through xAI's OpenAI-compatible API..."
---

# xAI (Grok) Connector for Muse

💳 Paid API required: this connector needs a paid third-party API — the listing is free, but usage is billed. See Prerequisites for costs.

A Muse agent skill that sends chat completions to Grok and lists the Grok models available to your API key, through xAI's OpenAI-compatible REST API. Every completion prints its token usage, so the cost is always visible (~$2.00/1M input and ~$6.00/1M output for the flagship at the time this was written) — confirm before large or repeated generations. Model ids move fast: prefer the live `models` output over any documented default. Uses an xAI API key (keys start with `xai-`), kept in Muse's secure vault. Draft: written from xAI's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-xai
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-xai
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/xai

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

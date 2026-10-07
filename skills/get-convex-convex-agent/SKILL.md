<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: get-convex-convex-agent
description: "Add an AI agent / RAG backend to your Convex app — no LLM key to rotate, gateway holds the creds"
---

# Convex AI Agent Backend

💳 Curated by Skill Harbor — installs @convex-dev/agent as the backend for an in-app AI agent: durable threads, message history, tool calls, and vector search/RAG. Model calls go through the Convex AI Gateway by default, which means Convex holds the provider credentials — no LLM API key for you to obtain, store, or rotate. RAG embeddings are stored in a vector index; the gateway doesn't serve embeddings yet, so the embedding provider's key stays in Convex env via the env micro power. Honest prerequisites: calling models through the gateway needs a Convex Cloud deployment on a paid plan (convex 1.45+); the fallback on free/self-hosted setups is a provider SDK key kept in Convex env. Never exposes a provider key client-side. By @get-convex, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/get-convex-convex-agent
- Fiche en français: https://theskillharbor.com/fr/products/get-convex-convex-agent
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/get-convex/agent-skills/blob/main/skills/convex-agent/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

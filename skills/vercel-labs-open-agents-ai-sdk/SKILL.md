<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: vercel-labs-open-agents-ai-sdk
description: "Work the Vercel AI SDK the current way — generateText/streamText, ToolLoopAgent, AI Gateway as..."
---

# AI SDK — build AI agents, chatbots, and RAG with the Vercel AI SDK

Curated by Skill Harbor — @vercel-labs's ai-sdk skill (from the open-agents collection): a discipline guide for building AI features with the Vercel AI SDK without tripping over outdated APIs. The core doctrine — "do not trust internal knowledge" — forces the agent to verify everything against the bundled docs in node_modules/ai/docs/ and source before writing code, install only the ai package first (providers and client packages later, as needed), default to the Vercel AI Gateway provider when choosing models, always fetch current model IDs from the gateway endpoint (newest version wins — never from memory), run typecheck after changes, and keep options minimal. It covers building and consuming agents with the ToolLoopAgent pattern, framework-specific consumption (detect the stack from package.json first), type-safe useChat via InferAgentUIMessage, devtools setup, and a common-errors reference for renamed parameters — with the pragmatic escape hatch of ai-sdk.dev doc search for older versions. Honest caveats: deliberately paranoid — the docs-first ritual adds lookups to every task, which is the point but also the cost; assumes a Node.js project with the SDK installed, not a general AI primer; model-ID advice will age, which is exactly why it insists on fetching. License: the manifest records MIT (the manifest makes faith); the repo frontmatter carries no license field. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/vercel-labs-open-agents-ai-sdk
- Fiche en français: https://theskillharbor.com/fr/products/vercel-labs-open-agents-ai-sdk
- Category: Dev
- Price: Free
- Verification: unverified
- Source repo: https://github.com/vercel-labs/open-agents/blob/main/.agents/skills/ai-sdk/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

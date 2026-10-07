<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: laguagu-claude-code-nextjs-skills-nextjs-chatbot
description: "Opinionated blueprint for production Next.js web chatbots: AI SDK 7 ToolLoopAgent..."
---

# Next.js Chatbot — production patterns for web chatbots (AI SDK 7)

Curated by Skill Harbor — @laguagu's nextjs-chatbot skill, listed here with credit to its creator: an opinionated blueprint for production web chatbots that covers the patterns the SDK docs skip. It gives the agent stack defaults (bun runtime, AI SDK 7 `ToolLoopAgent` with a v6 fallback table, shadcn/ui + ai-elements, Drizzle + PostgreSQL, Zustand client state), agent setup with portable reasoning-effort configuration, a route handler with consent gating and session upsert, human-in-the-loop tool approval with a 6-state render machine, message streaming-state handling (chat-level status, not tool-part states) to stop action-icon flicker, `MessageScroller` instead of hand-rolled stick-to-bottom, streaming-stable markdown via shadcn typeset, popup widget embedding (FAB + iframe + widget.js), SQL-first search guidance, per-tool UI rendering, message feedback persisted to the database, scope enforcement and prompt-injection defense blocks for the system prompt, grounding rules against hallucinated component names, and a testing split (UI harness without the model vs model benchmarks for stability). Honest caveats: opinionated stack (bun, Drizzle, shadcn) — adapt if yours differs; snippets are AI SDK v7 names and fail quietly on v6 codebases (check package.json); needs a billed model API key and PostgreSQL for full persistence; verify version-sensitive claims against the installed SDK, not this page. MIT licensed. Skill Harbor never reviews the code, review it yourself before...

- Listing: https://theskillharbor.com/products/laguagu-claude-code-nextjs-skills-nextjs-chatbot
- Fiche en français: https://theskillharbor.com/fr/products/laguagu-claude-code-nextjs-skills-nextjs-chatbot
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/laguagu/claude-code-nextjs-skills/blob/main/skills/nextjs-chatbot/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

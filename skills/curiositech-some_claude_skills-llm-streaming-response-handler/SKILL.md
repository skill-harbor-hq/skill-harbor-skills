<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: curiositech-some-claude-skills-llm-streaming-response-handler
description: "Build production-grade LLM streaming UIs with Server-Sent Events — token-by-token display..."
---

# LLM streaming response handler — production SSE streaming UIs with cancellation and error recovery

Curated by Skill Harbor — @curiositech's llm-streaming-response-handler skill: a complete guide to building production-grade streaming interfaces for LLM responses that feel instant. Covers why SSE beats WebSockets for one-way LLM streaming (simplicity, auto-reconnect, firewall-friendliness), the streaming formats of OpenAI/Anthropic/Vercel AI SDK, five common anti-patterns with fixes (buffering before display, no stream cancellation, no error recovery, memory leaks from unclosed streams, no typing indicator), and copy-ready implementation patterns — a basic SSE stream handler, a React useStreaming hook (content, isStreaming, error, stream, cancel), and a Next.js edge-runtime API route converting OpenAI streams to SSE — plus a 12-point production checklist (AbortController, error states with retry, typing indicator, cleanup on unmount, rate limiting, token tracking, streaming fallback, accessibility, mobile-friendly stop targets, network recovery, max length, cost estimation). Honest caveats: focused on one-way SSE streaming, not bidirectional WebSocket chat; API details (provider event formats, Vercel AI SDK) can drift over time. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/curiositech-some_claude_skills-llm-streaming-response-handler
- Fiche en français: https://theskillharbor.com/fr/products/curiositech-some_claude_skills-llm-streaming-response-handler
- Category: Dev
- Price: Free
- Verification: unverified
- Source repo: https://github.com/curiositech/some_claude_skills/blob/HEAD/.claude/skills/llm-streaming-response-handler/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

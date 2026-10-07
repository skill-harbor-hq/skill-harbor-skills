<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: rohitg00-agentmemory-session-history
description: "Show what happened in recent past sessions on this project as a clean reverse-chronological timeline"
---

# AgentMemory session history timeline

Curated by Skill Harbor — @rohitg00's user-invocable AgentMemory skill for answering "what did we do last time": call the `memory_sessions` tool and render a clean reverse-chronological timeline of recent project sessions — session id, project, start time, status, per-session observation counts, and key highlights (decisions, code, titles) when session summaries exist. Its central rule is anti-hallucination: only show sessions the tool actually returned, an empty history is a real answer never a cue to invent past work, and no session or highlight may be invented or merged. Points to sibling AgentMemory skills (`recap`, `handoff`, `recall`) for grouped or search-based views. Honest caveats: requires the AgentMemory tooling (`memory_sessions` and the shared troubleshooting reference) to be available — without it the skill has nothing to read; Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/rohitg00-agentmemory-session-history
- Fiche en français: https://theskillharbor.com/fr/products/rohitg00-agentmemory-session-history
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/rohitg00/agentmemory/blob/main/plugin/skills/session-history/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

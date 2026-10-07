<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: sulcus
description: "Thermodynamic memory for AI agents. Persistent, proactive, intelligent context that doesn't forget."
---

# Sulcus

AI agents forget. Context windows fill up, old facts disappear, and naive RAG pulls irrelevant noise. Sulcus is a persistent, proactive, intelligent memory engine for AI agents.

The core idea is simple: treat the prompt window like registers and long-term storage like RAM (a virtual memory management unit for your agent). Every memory carries heat (0.0 to 1.0). New facts start hot, unused ones cool down over time, frequently accessed ones stay warm, just like real memory. Recall doesn't rely on vector similarity alone: it combines semantic search, full-text with phrase proximity, thermodynamic heat, knowledge-graph neighbors, temporal recency, and keyword overlap.

What is inside:

- Thermodynamic decay: three modes (time-only, interaction-only, hybrid). Ignored memories fade, important ones persist.
- Knowledge graph: entities and relationships extracted automatically. Mentioning a topic warms related concepts through the graph.
- SIU pipeline: every stored memory passes a quality gate (rejects noise before storage), an automatic type classifier (episodic, semantic, fact, preference, procedural, synthesis), and entity extraction.
- Reactive triggers: rules that fire on memory events (store, recall, boost, decay): notify, boost, pin, tag, webhook. Your agent can react to its own memory changes instead of only answering queries.
- Context engine: manages the whole context window (constructive assembly, overflow prevention, working-memory cache, session knowledge...

- Listing: https://theskillharbor.com/products/sulcus
- Fiche en français: https://theskillharbor.com/fr/products/sulcus
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/digitalforgeca/sulcus

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

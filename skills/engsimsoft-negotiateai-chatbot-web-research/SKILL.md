<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: engsimsoft-negotiateai-chatbot-web-research
description: "Short listing — license not verifiable: a Russian-language skill for deep web research — query..."
---

# Web research (short listing)

Selected by Skill Harbor — short listing (the repo frontmatter carries no license field and the discovery manifest records null — the manifest makes faith, so no content is reproduced): @engsimsoft's web-research skill (part of the NegotiateAI-Chatbot project) — a web-research workflow skill written in Russian. It defines when to use deep search (fresh data, recent events, fact-checking, explicit "find it" requests) and when not to (general knowledge, historical facts, basic definitions), then runs a four-step process: formulate a concrete, minimal query in the language of the expected results (with good-vs-bad query examples), execute it via a `webSearch` tool call, process results (check publication dates, compare multiple sources, extract the essentials), and present an answer — not a dump — with sources cited and contradictions flagged. It notes the limitation: text-only search, no images. Honest caveats: license terms not verifiable — short listing with a link only, nothing copied; written in Russian — non-Russian users will need translation or a bilingual agent; it expects a host agent that actually provides a `webSearch` tool — without that tool the workflow has no execution path; a single-purpose utility, not a research system. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/engsimsoft-negotiateai-chatbot-web-research
- Fiche en français: https://theskillharbor.com/fr/products/engsimsoft-negotiateai-chatbot-web-research
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/engsimsoft/negotiateai-chatbot/blob/master/lib/prompts/skills/research/web-research/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

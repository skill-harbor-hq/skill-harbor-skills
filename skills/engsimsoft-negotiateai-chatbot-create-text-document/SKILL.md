<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: engsimsoft-negotiateai-chatbot-create-text-document
description: "Short listing — license not verifiable: a Russian-language skill for structured document drafting —..."
---

# Create text document (short listing)

Selected by Skill Harbor — short listing (the repo frontmatter carries no license field and the discovery manifest records null — the manifest makes faith, so no content is reproduced): @engsimsoft's create-text-document skill (part of the NegotiateAI-Chatbot project) — a document-drafting skill written in Russian. It instructs the agent to load it before creating any document, article, report or letter, then run a clarification pass (document type, audience, tone, length, format), pick the output format (plain text vs markdown), and generate via a `createDocument` tool call. It ships structure templates by document type (article/post, business letter, instructions, and more) so the output follows a consistent skeleton. Honest caveats: license terms not verifiable — short listing with a link only, nothing copied; written in Russian — non-Russian users will need translation or a bilingual agent to use it well; it expects a host agent that actually provides a `createDocument` tool (Claude Code-style tool skills) — without that tool the workflow has no execution path; a single-purpose utility, not a full writing system. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/engsimsoft-negotiateai-chatbot-create-text-document
- Fiche en français: https://theskillharbor.com/fr/products/engsimsoft-negotiateai-chatbot-create-text-document
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/engsimsoft/negotiateai-chatbot/blob/main/lib/prompts/skills/document/create-text-document/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

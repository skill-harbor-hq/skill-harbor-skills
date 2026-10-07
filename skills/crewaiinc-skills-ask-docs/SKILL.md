<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: crewaiinc-skills-ask-docs
description: "Answer any CrewAI question from the official live docs, via the docs MCP server or a WebFetch..."
---

# Ask the live CrewAI docs via MCP

Curated by Skill Harbor — a short pointer to @crewaiinc's ask-the-docs skill: answer any CrewAI question the sibling skills don't cover by querying the official live documentation — preferably through the crewai-docs MCP server (add https://docs.crewai.com/mcp as a remote MCP server), with a WebFetch fallback (docs index via llms.txt, then fetch the relevant page), synthesizing the answer and citing the source page. Honest caveats: **no license declared in the repository — license unknown**, so this is a short fiche linking to the source, without reusing its content; not for questions the curated sibling skills already answer; answers reflect the latest published docs, which can change. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/crewaiinc-skills-ask-docs
- Fiche en français: https://theskillharbor.com/fr/products/crewaiinc-skills-ask-docs
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/crewaiinc/skills/blob/main/.agents/skills/ask-docs/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

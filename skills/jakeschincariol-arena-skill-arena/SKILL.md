<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: jakeschincariol-arena-skill-arena
description: "When Claude keeps giving a bad answer, spin up N sub-agents (default 100, --quick for 16) with..."
---

# Arena , make N sub-agents compete in a tournament until one answer survives

Curated by Skill Harbor: for when Claude keeps giving a bad answer: instead of retrying, make 100 versions of it fight to the death. It spins up N sub-agents on the exact same task, each with a different strategy card (reasoning mode, workflow, strategy), runs a single-elimination bracket where they attack, defend and revise each other's solutions, and a judge scores every match on a written rubric until one answer survives. Ships with bracket.py for all the bookkeeping. by @Jakeschincariol, listed here with credit to its creator. Honest caveats: token-hungry by design, the default 100 agents means about 595 sub-agent calls, so use --quick (16 agents, 91 calls) for everyday use and confirm before launching a full run; the orchestrator never competes and never judges. Skill Harbor never reviews the code, review it yourself before use. Discovered via GitHub.

- Listing: https://theskillharbor.com/products/jakeschincariol-arena-skill-arena
- Fiche en français: https://theskillharbor.com/fr/products/jakeschincariol-arena-skill-arena
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Jakeschincariol/arena-skill/blob/main/skills/arena/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

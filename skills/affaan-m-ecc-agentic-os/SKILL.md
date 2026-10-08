<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-agentic-os
description: "Turn Claude Code into a persistent multi-agent OS: kernel config, specialist agents, slash..."
---

# Agentic OS

Curated by Skill Harbor: treat Claude Code as a persistent runtime and operating system rather than a chat session, codifying the architecture used by production agentic setups. Four layers, each a directory in your project root: the kernel (CLAUDE.md), which acts as the orchestrator with identity, routing rules, model policies and an agent registry; agents, the specialist identities with scoped tools and memory; commands, user-facing slash commands in .claude/commands such as /daily-sync; scripts, Python or JS daemons triggered by cron or webhooks; and state, an append-only JSON and markdown data layer with no external database. Configuration is git-tracked so the OS survives session restarts, while state can stay git-ignored. Covers when to build a personal OS for recurring tasks, structuring long-running projects where context must persist, and setting up scheduled automation that outlives any single session. From the affaan-m/ECC repository (MIT). Honest caveats: an architecture to build, not a one-click product; long-lived autonomous daemons need their own monitoring and cost controls. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-agentic-os
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-agentic-os
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/agentic-os/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

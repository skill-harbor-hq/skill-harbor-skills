<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-autonomous-agent-harness
description: "Turn Claude Code into a self-directing system with memory, scheduled tasks, dispatch, and computer..."
---

# Autonomous Agent Harness

Curated by Skill Harbor: a setup pattern that turns Claude Code into a fully autonomous agent system using its native pieces, presented as guidance rather than a bundled always-on runtime. Five components: persistent memory (built-in markdown memory plus an MCP knowledge graph server), scheduled operations (native crons for interactive sessions, an external scheduler for work that must survive a closed session), dispatch of remote agents via headless CLI from CI or webhooks, computer use through a separately configured integration with explicit permission grants, and a persistent task queue in memory files. Includes an MCP memory server setup guide (with a pinned, registry-verified package version and a warning never to register guessed npm names), cron pattern table (daily standup, weekly review, hourly monitor, nightly build), a Hermes-to-ECC component mapping, and example workflows (autonomous PR reviewer, personal research agent, meeting prep agent). The skill itself states strong consent and safety boundaries: autonomous operation must be explicitly requested and scoped by the user, prefer dry-run plans and local queue files first, keep credentials and private automations out of reusable artifacts. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: Claude Code-specific (native crons, ~/.claude paths, CLI); inside Muse use it as setup guidance, some parts do not map one to one. Computer use needs its own...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-autonomous-agent-harness
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-autonomous-agent-harness
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/autonomous-agent-harness/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

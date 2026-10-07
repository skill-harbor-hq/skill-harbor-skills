<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: wshobson-agents-team-composition-patterns
description: "Sizing heuristics, preset teams (review, debug, feature, security), agent-type selection and..."
---

# Team composition patterns — build the right agent team

Curated by Skill Harbor — a multi-agent playbook by @wshobson for composing agent teams in Claude Code's Agent Teams feature: team-sizing heuristics by complexity (1–2 for simple up to 4–5 for very complex, with "start with the smallest team that covers all dimensions"), seven preset compositions (Review, Debug, Feature, Fullstack, Research, Security, Migration teams) with sizes, agent roles, and when-to-use triggers, an agent-type selection table (general-purpose vs read-only Explore/Plan vs specialized team-reviewer/debugger/implementer/lead with their tool sets), display-mode configuration (tmux, iTerm2, in-process for CI), custom-team guidelines, and a troubleshooting section covering the classic failure modes (read-only agents assigned writes, oversized teams, duplicate review dimensions, teammates not receiving tasks). Honest caveats: the mechanics (subagent_type, teammateMode, the team-* agent roles) are specific to Claude Code's Agent Teams — the heuristics and presets transfer, the configuration syntax does not; coordination overhead grows fast past 4–5 teammates. Credit to its creator. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/wshobson-agents-team-composition-patterns
- Fiche en français: https://theskillharbor.com/fr/products/wshobson-agents-team-composition-patterns
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/wshobson/agents/blob/main/plugins/agent-teams/skills/team-composition-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-claude-devfleet
description: "Dispatch parallel Claude Code agents in isolated git worktrees with Muse: plan a project into a..."
---

# Claude DevFleet Multi-Agent Orchestration

Curated by Skill Harbor: a full multi-agent orchestration workflow on top of the Claude DevFleet server. The flow is Plan, Dispatch, Monitor, Report. plan_project turns a plain-language description into a project with a mission DAG, chained by depends_on with auto_dispatch set; you show the plan, get approval, then dispatch the root mission while the rest auto-start as dependencies complete. Each agent runs in an isolated git worktree with full tooling and auto-merges on completion. Tools cover the whole lifecycle: create_project, create_mission, dispatch_mission, cancel_mission, wait_for_mission (blocks up to the timeout, prefer polling get_mission_status every 30-60 seconds for long runs), get_report (files changed, what was done, errors, next steps), get_dashboard (running agents, stats, activity), list_projects, list_missions. Concurrency runs up to 3 agents by default via DEVFLEET_MAX_AGENTS, with the mission watcher queueing the rest. Guidelines are firm: always confirm the plan with the user before dispatching unless they said go ahead, read a failed mission's report before retrying, never create circular dependencies, and merge conflicts stay on the agent's worktree branch for manual resolution. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: the DevFleet server is a separate project (github.com/LEC-AI/claude-devfleet) you install and run yourself, then connect over MCP to localhost:18801; verify the...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-claude-devfleet
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-claude-devfleet
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/claude-devfleet/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

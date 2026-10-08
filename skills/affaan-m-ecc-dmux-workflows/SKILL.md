<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-dmux-workflows
description: "Orchestrate parallel AI agent sessions with dmux, a tmux pane manager for agents..."
---

# dmux Workflows

Curated by Skill Harbor: a pattern guide for running multiple AI agent sessions in parallel with dmux, a tmux pane manager for agent harnesses (press n for a new pane with a prompt, m to merge output back). Five workflow patterns are spelled out with concrete pane assignments: research plus implement with findings merged into the builder's context; multi-file features split across schema, API, and UI panes with integration in the main pane; test plus fix loops with a watcher pane and a fixer pane; cross-harness work mixing Claude Code, Codex, and others by task fit; and parallel code review with security, performance, and coverage perspectives merged into one report. Best practices are firm: independent tasks only, clear file boundaries, strategic merging, git worktrees for conflict-prone work, and resource awareness since each pane is a full agent session, keep it to five or six panes. It also documents the ECC helper script for external tmux-pane orchestration with branch-backed worktrees, per-worker task and handoff files, and seed paths for dirty local files, plus a troubleshooting section for unresponsive panes, merge conflicts, high token usage, and missing tmux. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: dmux itself is a separate install from github.com/standardagents/dmux; every parallel pane burns API tokens, so small tasks are cheaper in a single session. Skill Harbor never reviews the code, review...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-dmux-workflows
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-dmux-workflows
- Category: Orchestration
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/dmux-workflows/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

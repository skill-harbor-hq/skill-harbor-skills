<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: foremerge
description: "Catch intent conflicts before code conflicts: the open-source coordination protocol for coding..."
---

# Foremerge

Foremerge is the open-source coordination protocol for coding agents, built above Git. Run Claude Code in one worktree, Codex in another, or any other agents from any provider: each agent declares what it is about to change (intents, semantic scopes like symbol:PaymentService=replace, dependencies, provisional ChangeSets, decisions) through one shared SQLite store under your repository's Git common directory. When two plans collide, deterministic rules raise an explainable finding while the work is still a plan, with the rule that fired and a suggested resolution. Git still stores the commits; Foremerge stores the shared plan.

It is a coordinator, not an orchestrator: claims are leased and advisory, never locks, and nothing ever blocks an agent. The full lifecycle is exposed over a local CLI, a JSON API and an MCP server (17 tools), with one-command client wiring (foremerge setup all handles Claude Code, Codex and Cursor). Acceptance is verification-gated: Foremerge runs your trusted check itself rather than taking an agent's word for it.

Honest caveats: this is a pre-1.0 local-first MVP (0.5.1), so public schemas may still change. Published benchmark results do not exist yet, and coordination between machines is out of scope. Conflict detection is heuristic and advisory: it warns, it never locks.

- Listing: https://theskillharbor.com/products/foremerge
- Fiche en français: https://theskillharbor.com/fr/products/foremerge
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/naw103/foremerge

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

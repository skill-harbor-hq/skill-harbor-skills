<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-ck
description: "Give Muse persistent per-project memory with ck (Context Keeper): deterministic /ck commands to..."
---

# ck: Context Keeper

Curated by Skill Harbor: ck (Context Keeper), a community skill by sreedhargs89 (MIT, from github.com/sreedhargs89/context-keeper) listed here via affaan-m/ECC, that gives Muse persistent per-project memory driven by deterministic Node.js scripts instead of vibes. The data layout is simple: a projects.json registry and per-project contexts with context.json as the source of truth plus a generated CONTEXT.md view you never hand-edit. The command set covers the whole lifecycle: /ck:init registers a project with auto-detected name, description, stack, goal, constraints, and repo, presented as a confirmation draft before saving; /ck:save is the only command requiring LLM analysis, distilling the session into a summary, where it left off, next steps, decisions with reasons, blockers, and a goal update only if it changed, shown as a draft for approval before writing; /ck:resume gives a full briefing and asks whether anything changed; /ck:info gives a quick snapshot; /ck:list gives a portfolio view; /ck:forget asks for explicit confirmation before permanently deleting a context; /ck:migrate converts v1 data to v2 with backups kept. A SessionStart hook injects a compact five-line brief at about 100 tokens per session and detects unsaved sessions, git activity since the last save, and goal mismatches against CLAUDE.md. By sreedhargs89, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: the Node scripts must be installed at...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-ck
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-ck
- Category: Memory
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/ck/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: andrelandgraf-fullstackrecipes-ralph-loop
description: "Run a coding agent in a long autonomous loop: wide outcome-focused prompt, CLI/auth preflight..."
---

# Ralph loop — autonomous coding-agent iterations with preflight checks (short pointer)

Curated by Skill Harbor — a short pointer to @andrelandgraf's Ralph loop workflow: drive long-running autonomous development from a wide, outcome-focused prompt by letting the agent's own harness manage the todo list. The loop starts with a preflight check (every CLI installed, linked and authenticated — the agent infers the infra from the codebase and reports fix commands for anything red, and never starts until everything is green), then iterates: break remaining work into first-principles tasks, implement with tests and user-facing docs, verify with typecheck, format, tests and browser checks, commit and move on. The durable record of intent lives in the artifacts produced — tests as executable acceptance criteria, docs, and changelogs. Honest caveats: **no license declared in the repository manifest — license unknown**, so this is a short fiche linking to the source, without reusing its content; it assumes a fullstack-recipes-style setup (agent-browser, Vercel/Neon/Sentry CLIs) — adapt the preflight and verification commands to your own stack; a runaway loop can burn a lot of agent time, so keep an eye on it. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/andrelandgraf-fullstackrecipes-ralph-loop
- Fiche en français: https://theskillharbor.com/fr/products/andrelandgraf-fullstackrecipes-ralph-loop
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andrelandgraf/fullstackrecipes/blob/main/skills/ralph-loop-workflow/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

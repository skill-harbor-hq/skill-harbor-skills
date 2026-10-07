<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: cursor-plugins-why
description: "Answer \"why does this code exist\" with parallel investigator agents over git, tickets, docs, chat..."
---

# Why — multi-source design-rationale investigations (short pointer)

Curated by Skill Harbor — a short pointer to @cursor's why skill: a rigorous methodology for answering "why does this code work this way" instead of "what does it do". The workflow anchors the investigation in concrete code (blame, log, PR numbers), then spawns parallel investigator agents — one per evidence category: source control, issue tracker, long-form docs, team chat, infrastructure observability, error tracking, product analytics warehouse — over the MCPs available in the environment, and synthesizes the findings under a strict epistemics framework (what we know, what we infer, competing hypotheses, what we don't know, one line per source consulted). Honest caveats: **no license declared in the repository manifest — license unknown**, so this is a short fiche linking to the source, without reusing its content; it is built for Cursor's environment (MCP discovery, Task subagents, `pstack-models.mdc` model slugs) — adapt the orchestration to your own agent harness; expect heavy compute on wide sweeps. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/cursor-plugins-why
- Fiche en français: https://theskillharbor.com/fr/products/cursor-plugins-why
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/cursor/plugins/blob/main/pstack/skills/why/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

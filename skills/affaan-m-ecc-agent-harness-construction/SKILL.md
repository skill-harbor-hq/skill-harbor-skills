<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-agent-harness-construction
description: "Design better AI agents: action space design, tool definitions, observation formatting, error..."
---

# Agent Harness Construction

Curated by Skill Harbor: a skill for people who build AI agents and want them to actually finish the job. It treats agent quality as a design problem constrained by four things: action space quality, observation quality, recovery quality, and context budget quality. You get concrete rules: stable explicit tool names, schema-first narrow inputs, deterministic output shapes, micro-tools for high-risk operations (deploy, migration, permissions) and macro-tools only when round-trip overhead dominates; every tool response carrying status, a one-line summary, next actions, and artifact references; an error recovery contract for every error path (root-cause hint, safe retry instruction, explicit stop condition); and context budgeting that keeps the system prompt minimal, moves guidance into on-demand skills, prefers file references over inlined documents, and compacts at phase boundaries. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: design guidance, not a framework; better harnesses raise completion rates but cannot fix a weak model or a vague task. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-agent-harness-construction
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-agent-harness-construction
- Category: AI Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/agent-harness-construction/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

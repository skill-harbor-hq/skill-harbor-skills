<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-blueprint
description: "Turn a one-line objective into a step-by-step build plan with dependency graph, parallel steps, and..."
---

# Blueprint

Curated by Skill Harbor: a planning skill that turns a one-line objective ("migrate the database to PostgreSQL") into a step-by-step construction plan any coding agent can execute cold. It runs a 5-phase pipeline: research (pre-flight checks, project structure, memory files), design (one-PR-sized steps, 3 to 12 typical, with dependency edges, parallel or serial ordering, model tier per step, and rollback strategy), draft (a self-contained Markdown plan file where every step carries its own context brief, task list, verification commands, and exit criteria, so a fresh agent can run any step without reading the others), review (an adversarial review pass against a checklist and anti-pattern catalog, with critical findings fixed before finalizing), and register (plan saved, memory index updated, step count and parallelism summary presented). It detects git and GitHub CLI availability automatically and degrades gracefully to direct edit-in-place mode when they are absent. Pure Markdown skill: the repository contains only .md files, no hooks, no shell scripts, no executable code, nothing runs on install. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: written around a /blueprint slash command in Claude Code, so in Muse you paste the SKILL.md and drive the 5 phases conversationally instead; not for single-PR tasks or when you just want the work done now. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-blueprint
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-blueprint
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/blueprint/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

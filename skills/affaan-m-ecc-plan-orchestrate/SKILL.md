<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-plan-orchestrate
description: "Turn plan documents into agent chains for Muse: decomposes each step, picks the right ECC agents..."
---

# Plan Orchestrate

Curated by Skill Harbor: a bridge from a plan document to driven multi-agent execution, so Muse turns your PRD or RFC into ready-to-paste orchestration commands instead of you composing agent chains by hand. Generative only, it never invokes /orchestrate itself, you paste each line when ready. Works in five phases: detect the ECC install form (plugin versus legacy, so command and agent prefixes stay in sync) and the project language (polyglot-aware, with a PyTorch sub-profile) ; decompose the plan into step units from numbering, tables or headings ; tag each step by intent (design, plan, impl, test, refactor, migration, db, security, build, docs, lookup, review, loop) and compose a chain of up to four agents from the ECC catalogue with composition rules (security-sensitive impl ends with security-reviewer, db work gates through database-reviewer, impl steps end with a reviewer) ; compress each step into a self-contained one-line task description with acceptance criteria and inherited scope guards ; then emit Markdown with an overview table, per-step bash blocks, and a batch execution block, followed by a self-check (catalogue names only, uniform prefix form, no invented flags). Handles edge cases: no clear steps, large plans (overview-only mode), over-broad steps, plan-declared agents, polyglot ties. Use when you have a multi-step plan and want to drive it through orchestration without hand-composing chains. By @affaan-m, listed here with credit to its creator. From the...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-plan-orchestrate
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-plan-orchestrate
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/plan-orchestrate/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

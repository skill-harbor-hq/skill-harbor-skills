<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: addyosmani-planning-and-task-breakdown
description: "Break big builds into small, verifiable, shippable tasks"
---

# Planning and Task Breakdown Skill for Muse

The difference between an agent that finishes work reliably and one that produces a tangled mess: it turns a spec or clear requirements into small, verifiable tasks with explicit acceptance criteria. The method has five steps: enter read-only plan mode before writing any code; map the dependency graph (build foundations first, bottom-up); slice vertically so each task delivers one complete working feature path instead of a horizontal layer of everything; write tasks with a fixed structure (acceptance criteria, verification step, dependencies, files touched, XS-to-XL sizing); then order them with checkpoints every 2-3 tasks and high-risk work early. Output conventions are fixed too: plan in `tasks/plan.md`, task list in `tasks/todo.md` (or an external tracker like GitHub Issues, Jira, or Linear when the project designates one) — and the skill's hard rule is to never overwrite an incomplete plan for different work without asking first. Includes sizing guidelines, parallelization rules for multi-agent work, a "Common Rationalizations" table ("planning is overhead" vs "planning is the task"), and red flags such as tasks without acceptance criteria. Discovered via skills.sh. Honest note: it assumes you already have a spec or clear requirements — it tells you when NOT to use it (single-file changes with obvious scope), and it plans implementation only, not product discovery or requirement gathering. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/addyosmani-planning-and-task-breakdown
- Fiche en français: https://theskillharbor.com/fr/products/addyosmani-planning-and-task-breakdown
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/addyosmani/agent-skills/blob/main/skills/planning-and-task-breakdown/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

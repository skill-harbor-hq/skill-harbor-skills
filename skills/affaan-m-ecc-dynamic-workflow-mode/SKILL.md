<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-dynamic-workflow-mode
description: "Stop improvising agent workflows with Muse: design task-local harnesses with objective, inputs..."
---

# Dynamic Workflow Mode Harnesses

Curated by Skill Harbor: a discipline for Claude dynamic workflow mode that turns ad-hoc agent improvisation into an observable system. The core contract: a task-local harness is only worth building when it is cheaper and safer than manually driving the same steps, and it must declare its Objective (what it owns and explicitly does not own), Inputs (files, URLs, prompts, data sources, credentials policy, constraints), Outputs (commits, reports, screenshots, status files, control pane snapshots), Eval (at least one pass/fail check tied to the task, never just "it ran"), and Handoff (a short artifact telling the next operator what happened, what is blocked, and how to resume). The decision tree keeps you honest: one-shot task stays inline, repeated task with changing inputs gets a task-local harness in a temp or project-local area, repeated task across teammates or repos gets extracted into a shared skill, tasks with external state or approvals get control pane visibility first, and safety-risky tasks get an eval gate plus a human merge gate before autonomous execution. Control pane checkpoints (Plan, Queue, Run, Gate, Handoff) make the workflow team-usable across sessions, and eval gates are chosen per work type: focused tests for code, browser smoke for UI, fixture transcripts for agent workflows, claim checklists for research, dry runs for integrations. Shared skill extraction is gated too: promote only when at least two signals hold (the workflow repeats across sessions or...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-dynamic-workflow-mode
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-dynamic-workflow-mode
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/dynamic-workflow-mode/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-parallel-execution-optimizer
description: "Speed up agent work with Muse: turn tasks into dependency graphs of parallel lanes with isolated..."
---

# Parallel Execution Optimizer

Curated by Skill Harbor: an execution pattern that makes Muse turn urgency into a dependency graph before acting, so parallel agent work stays fast and correct. The core pattern is seven steps: define the objective and done signal, split work into lanes, mark each lane as parallel, sequential or gated, run independent reads and checks together, keep write surfaces isolated by file, worktree, branch, service or dataset, merge only after evidence shows the lanes are compatible, and end with a verification table instead of a vague speed claim. A lane matrix template shows the shape to fill before a large push: lane name, can it run in parallel, write surface, risk, verification. Execution rules cover batching reads and checks, isolated worktrees for large unrelated implementation lanes, starting long tests and builds in separate sessions, pausing dependent lanes when a blocker changes the plan, and never letting a background process outlive the turn unless asked. The output shape is a compact report with lanes run, completed, blocked and the fast path found, and the failure modes are honest: more concurrency creating conflicting edits, treating fast as done before correctness is proven, forgetting to poll running sessions. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: never parallelize destructive commands, migrations, writes to the same table, or live customer-impacting deploys without an explicit gate; speed is a...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-parallel-execution-optimizer
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-parallel-execution-optimizer
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/parallel-execution-optimizer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

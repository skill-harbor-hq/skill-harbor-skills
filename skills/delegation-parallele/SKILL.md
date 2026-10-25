<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: delegation-parallele
description: "Delegate long work to subagents in parallel, in waves of 2 to 5 maximum, without ever blocking the..."
---

# Délégation parallèle

Parallel Delegation is a working method for long, multi-step, self-contained work: delegate to subagents in parallel when tasks are independent, and never block the main agent. Golden rule: keep juice to answer — the main agent coordinates and answers, it does not run the heavy work. Waves of 2 by default, 5 maximum (10 once hit a rate limit and killed agents); dependent chains get a single coordinator, sequential execution, full validation per step, clean stop at the first failure. Briefs are self-sufficient, results are reported piece by piece as they land, and separate compute is parallelized without removing the go, the agent ceiling, or external delays. Stop is final and instant: everything halts in the same turn, confirmed by a verified fact. Pure guidance: no scripts, no tools, no accounts — it authorizes no publication, deployment, or production writes.

- Listing: https://theskillharbor.com/products/delegation-parallele
- Fiche en français: https://theskillharbor.com/fr/products/delegation-parallele
- Category: Developer tools
- Price: Free
- Verification: verified
- Source repo: n/a

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

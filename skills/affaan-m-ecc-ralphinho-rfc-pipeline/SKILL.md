<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-ralphinho-rfc-pipeline
description: "Split an oversized RFC into a multi-agent execution DAG with Ralphinho: work units with..."
---

# Ralphinho RFC Pipeline

Curated by Skill Harbor: the Ralphinho RFC pipeline, inspired by humanplane-style RFC decomposition patterns, for features too large for a single agent pass. The pipeline runs seven stages: RFC intake, DAG decomposition into work units with explicit dependencies, unit assignment, unit implementation, unit validation, merge queue and integration, and final system verification. Every work unit carries a spec with id, depends_on, scope, acceptance_tests, risk_level, and rollback_plan. Three complexity tiers sort the units: isolated file edits with deterministic tests at tier 1, multi-file behavior changes with moderate integration risk at tier 2, and schema, auth, performance, or security changes at tier 3. Each unit runs its own quality pipeline of research, implementation plan, implementation, tests, review, and a merge-ready report. The merge queue rules are strict: never merge a unit with unresolved dependency failures, always rebase unit branches on the latest integration branch, re-run integration tests after each queued merge. Recovery is defined too: evict a stalled unit, snapshot findings, regenerate a narrowed scope, retry with updated constraints. Outputs are an RFC execution log, unit scorecards, a dependency graph snapshot, and an integration risk summary. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this is a workflow wrapper, not an orchestrator runtime; for small features a single pass is cheaper...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-ralphinho-rfc-pipeline
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-ralphinho-rfc-pipeline
- Category: Orchestration
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/ralphinho-rfc-pipeline/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

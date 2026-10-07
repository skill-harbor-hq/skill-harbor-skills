<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: seb1n-awesome-ai-agent-skills-ml-pipeline-creation
description: "A platform-neutral method for designing reproducible ML pipelines — stage DAGs with explicit..."
---

# ML Pipeline Creation — reproducible pipelines from data to deployment gates

Curated by Skill Harbor — @seb1n's ml-pipeline-creation skill, listed here with credit to its creator: a platform-neutral method for an agent to design, implement and validate reproducible machine-learning pipelines — starting from required inputs (business objective, measurable acceptance criteria, data ownership and refresh cadence, target environments, compute/cost/compliance constraints), then an output contract (stage dependency graph, versioned pipeline definition, explicit input/output schemas, data/model/environment versioning rules, evaluation and promotion gates with failure behavior, observability/retry/backfill/rollback procedures, and a verification record). The workflow stresses inspecting the environment before picking tools ("don't introduce a platform merely to demonstrate one"), modeling the DAG as idempotent stages with declared artifacts, pinning dependencies and seeds, quality gates that fail closed, retries only for transient failures, and incremental testing — including forcing one stage to fail to verify downstream stages never execute silently. It also documents edge cases (streaming data, non-deterministic training, large backfills, schema drift, partial promotion). Honest caveats: methodology guidance, not a ready-made orchestrator — your team supplies the actual platform (Airflow, Kubeflow, CI runners); safety boundaries are spelled out (no production data in dev without authorization, no production promotion without explicit approval) but the...

- Listing: https://theskillharbor.com/products/seb1n-awesome-ai-agent-skills-ml-pipeline-creation
- Fiche en français: https://theskillharbor.com/fr/products/seb1n-awesome-ai-agent-skills-ml-pipeline-creation
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/seb1n/awesome-ai-agent-skills/blob/main/ai-ml-operations/ml-pipeline-creation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

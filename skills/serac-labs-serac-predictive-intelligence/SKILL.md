<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: serac-labs-serac-predictive-intelligence
description: "Use ServiceNow Predictive Intelligence from the agent: sn_ml.ClassificationPredictor for..."
---

# Predictive Intelligence for ServiceNow — auto-categorization, similarity and clustering

Curated by Skill Harbor — @serac-labs's predictive-intelligence skill, listed here with credit to its creator: a developer playbook for driving ServiceNow Predictive Intelligence from an agent — configuring classification solutions (the `ml_solution` table: target field, input fields, capability type), getting predictions with `sn_ml.ClassificationPredictor` (predicted value, confidence, top predictions), auto-applying classifications to records, using `SimilarityPredictor` to find related records and `ClusteringPredictor` to group related items, plus regression and recommendation capabilities, model training/retraining flows, and prediction-feedback accuracy tracking. It documents the key tables (`ml_solution`, `ml_solution_definition`, `ml_capability_definition`, `ml_model`, `ml_prediction_result`) and the available agent tools (snow_query_table, snow_execute_script, snow_ml_predict, snow_list_pi_solutions, snow_train_pi_solution). Honest caveats: everything here runs inside a ServiceNow instance — you need one to use it (ServiceNow offers a free Personal Developer Instance for dev work; production requires a licensed instance) — and the agent tools it references assume the Serac skill/tooling environment is configured; classification models trained on your incident data need periodic retraining and feedback tracking to stay accurate, and auto-applying predictions to production records can change live data — review before enabling. Apache-2.0 licensed. Skill Harbor never...

- Listing: https://theskillharbor.com/products/serac-labs-serac-predictive-intelligence
- Fiche en français: https://theskillharbor.com/fr/products/serac-labs-serac-predictive-intelligence
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/serac-labs/serac/blob/main/packages/skills/predictive-intelligence/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

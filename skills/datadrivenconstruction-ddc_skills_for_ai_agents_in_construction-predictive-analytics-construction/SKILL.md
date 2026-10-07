<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: datadrivenconstruction-ddc-skills-for-ai-agents-in-construction
description: "Forecast project outcomes from historical data: cost overruns, schedule delays, and risk..."
---

# Predictive Analytics for Construction — forecast overruns, delays, and risks

Curated by Skill Harbor — @datadrivenconstruction's predictive-analytics-construction skill, listed here with credit to its creator (companion to the "Data-Driven Construction" book, chapter 4.1): turn historical project data into forward-looking risk intelligence. It ships a complete `ConstructionPredictiveAnalytics` Python class — train a cost-overrun model (GradientBoostingRegressor on estimate vs final cost with feature importance), a schedule-delay classifier (GradientBoostingClassifier on planned vs actual duration), query predictions for new projects with confidence and ranked risk factors, find similar historical projects via nearest-neighbors for comparable outcomes, and generate a full markdown prediction report. Honest caveats: needs real historical data with the expected columns (estimates, final costs, durations, change orders, complexity scores) — the code is a framework, not a pretrained model; the confidence values are simplified approximations, not calibrated probabilities; pair it with the sibling cost-prediction skill for deeper model comparison. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/datadrivenconstruction-ddc_skills_for_ai_agents_in_construction-predictive-analytics-construction
- Fiche en français: https://theskillharbor.com/fr/products/datadrivenconstruction-ddc_skills_for_ai_agents_in_construction-predictive-analytics-construction
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/datadrivenconstruction/ddc_skills_for_ai_agents_in_construction/blob/main/2_DDC_Book/4.1-Analytics-KPI-Dashboard/predictive-analytics-construction/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

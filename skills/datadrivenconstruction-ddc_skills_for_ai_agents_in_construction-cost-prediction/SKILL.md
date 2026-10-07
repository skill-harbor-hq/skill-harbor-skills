<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: datadrivenconstruction-ddc-skills-for-ai-agents-in-construction
description: "Predict construction project costs with machine learning: Linear Regression, KNN, Random Forest..."
---

# Construction Cost Prediction — ML models for forecasting project costs

Curated by Skill Harbor — @datadrivenconstruction's cost-prediction skill, listed here with credit to its creator (companion to the "Data-Driven Construction" book, chapter 4.5): forecast construction project costs from historical data using classical machine learning. It walks the agent through the full pipeline — preparing historical project datasets (missing values, categorical encoding, derived features like cost-per-m², inflation adjustment), feature engineering (interactions, polynomial features, log transforms, size binning), training and comparing Linear Regression, K-Nearest Neighbors (with GridSearchCV), Random Forest, and Gradient Boosting models with MAE/RMSE/R²/MAPE evaluation and cross-validation, then packaging the winner into a reusable prediction function with confidence ranges and joblib save/load. Honest caveats: predictions are only as good as the historical data — garbage in, garbage out; the worked examples are generic templates you adapt to your own schema; the inflation baseline is hardcoded to 2024 and needs updating; always present prediction ranges, not point estimates, for real budgeting decisions. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/datadrivenconstruction-ddc_skills_for_ai_agents_in_construction-cost-prediction
- Fiche en français: https://theskillharbor.com/fr/products/datadrivenconstruction-ddc_skills_for_ai_agents_in_construction-cost-prediction
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/datadrivenconstruction/ddc_skills_for_ai_agents_in_construction/blob/main/2_DDC_Book/4.5-ML-Cost-Prediction/cost-prediction/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

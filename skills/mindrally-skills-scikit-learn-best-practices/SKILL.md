<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mindrally-skills-scikit-learn-best-practices
description: "Split-before-preprocess, pipelines and column transformers against data leakage, stratified CV..."
---

# scikit-learn best practices: leak-proof pipelines, CV, tuning, and evaluation

Curated by Skill Harbor — @mindrally's scikit-learn best-practices skill: the full discipline of a sound ML workflow — split data before any preprocessing (stratified for imbalanced classes), always chain preprocessing and modeling in `Pipeline`/`ColumnTransformer` so transformers fit only on training data, scale per algorithm (StandardScaler/MinMaxScaler/RobustScaler), encode categoricals, impute missing values, cross-validate with the right strategy (`KFold`, `StratifiedKFold`, `TimeSeriesSplit`, `GroupKFold`), tune with `GridSearchCV`/`RandomizedSearchCV` on train/val only with `n_jobs=-1`, evaluate with metrics matched to the problem (F1/ROC-AUC for imbalance, MAE/R² for regression), report confidence intervals against meaningful baselines, evaluate on the held-out test set once at the end, persist whole pipelines with joblib, and version model artifacts. Honest caveats: methodology only — the agent needs an ML dataset and a Python environment; some rules (e.g. `class_weight='balanced'`) are scikit-learn-specific. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mindrally-skills-scikit-learn-best-practices
- Fiche en français: https://theskillharbor.com/fr/products/mindrally-skills-scikit-learn-best-practices
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mindrally/skills/blob/main/scikit-learn-best-practices/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

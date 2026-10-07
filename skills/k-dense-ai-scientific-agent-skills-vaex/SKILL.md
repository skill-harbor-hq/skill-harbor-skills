<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: k-dense-ai-scientific-agent-skills-vaex
description: "Process massive tabular datasets with lazy, memory-mapped Vaex DataFrames — filtering, virtual..."
---

# Vaex out-of-core DataFrames: analyze billions of rows without the RAM

Curated by Skill Harbor — @k-dense-ai's Vaex skill for analyzing tabular datasets too large for RAM — billions of rows processed at over a billion rows per second via lazy, memory-mapped, out-of-core DataFrames. Covers six capability areas: DataFrames and data loading (HDF5, CSV, Arrow, Parquet, pandas/NumPy conversion), data processing and manipulation (filtering, virtual columns, expressions, groupby aggregations), performance and optimization (lazy evaluation, delay=True batching, caching), data visualization (heatmaps, histograms, scatter plots via df.viz), machine learning integration (scalers, encoders, PCA, K-means, scikit-learn/XGBoost/CatBoost), and I/O (format recommendations, export strategies). Includes concrete common patterns: converting a large CSV to HDF5 for instant future loads, batching multiple aggregations with delay=True, and feature engineering with zero-memory-overhead virtual columns. States the Vaex-vs-alternatives rule honestly: polars when data fits in RAM and you need max in-memory speed, dask for distributed clusters, Vaex for single-machine out-of-core analytics. Honest caveats: requires Python 3.10+ (3.12+ recommended with vaex 4.19.0); the skill asks that substantial use be cited in manuscripts (arXiv:2609.00065). MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/k-dense-ai-scientific-agent-skills-vaex
- Fiche en français: https://theskillharbor.com/fr/products/k-dense-ai-scientific-agent-skills-vaex
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/k-dense-ai/scientific-agent-skills/blob/main/skills/vaex/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

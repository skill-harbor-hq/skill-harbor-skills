<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mindrally-skills-numpy-best-practices
description: "Vectorized ufuncs and broadcasting over loops, views over copies, dtype discipline, memory-layout..."
---

# NumPy best practices: vectorization, dtypes, and memory-efficient array programming

Curated by Skill Harbor — @mindrally's NumPy best-practices skill for writing idiomatic, fast numerical Python: always prefer vectorized ufuncs and broadcasting over explicit loops, pick array-creation and combination routines deliberately (`np.zeros`/`np.empty` pre-allocation, `vstack`/`hstack`/`concatenate`), use boolean advanced indexing and `np.where()`, understand views vs fancy-index copies, declare dtypes explicitly (`float32` when precision allows, guard against integer overflow), check memory layout with `ndarray.flags` and prefer in-place `out=` operations, handle NaN/Inf with `isnan`/`isinf` under `np.errstate()`, use the modern `np.random.default_rng()` generator API, solve linear systems with `linalg.solve` instead of inverting, and test with `pytest` + `np.testing` assertions in NumPy docstring style. Honest caveats: methodology only, no tooling — the agent needs a NumPy project to apply it to; NumPy-version-specific behaviors (e.g. RNG API) evolve, pin the version in your project. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mindrally-skills-numpy-best-practices
- Fiche en français: https://theskillharbor.com/fr/products/mindrally-skills-numpy-best-practices
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mindrally/skills/blob/main/numpy-best-practices/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

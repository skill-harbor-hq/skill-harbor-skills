<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-recsys-pipeline-architect
description: "Design composable recommendation and feed pipelines: Source, Hydrator, Filter, Scorer, Selector..."
---

# Recsys Pipeline Architect

Curated by Skill Harbor: a recommendation pipeline architect skill for designing the plumbing around your ranking model, not the model itself. It uses a six-stage framework popularized by xAI's open-sourced For You algorithm: Source fetches candidates from one or more origins (parallel), Hydrator enriches each candidate with metadata (parallel), Filter drops what should never be shown like blocked, expired, or duplicate items (sequential), Scorer assigns scores (sequential, later scorers see earlier scores), Selector sorts and returns the top K (single op), and SideEffect caches served IDs, logs impressions, and emits events asynchronously without ever blocking the response. It explains why the order matters (know candidates before paying to enrich them, filter before scoring to save compute) and produces runnable scaffolds in TypeScript, Go, or Python for feeds, RAG rerankers, notification triage, search reranking, or ad ranking. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT); the six-stage pattern is attributed to xAI's For You algorithm (Apache 2.0). Honest caveats: pure architecture guidance, nothing to install; the scoring function is your responsibility, this is the plumbing around it; not for model architecture work or operating a deployed pipeline. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-recsys-pipeline-architect
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-recsys-pipeline-architect
- Category: Machine Learning
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/recsys-pipeline-architect/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

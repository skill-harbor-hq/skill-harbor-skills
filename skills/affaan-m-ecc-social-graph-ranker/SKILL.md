<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-social-graph-ranker
description: "Rank your X and LinkedIn network by warm-intro value with a transparent weighted graph model."
---

# Social Graph Ranker

Curated by Skill Harbor: the standalone math engine behind warm-intro discovery on X and LinkedIn. Given a weighted target set and your current graph, it computes bridge scores with hop decay (each extra hop halves the contribution), second-order expansion for friends of friends, and a responsiveness-adjusted final ranking, then returns tiered results: best warm intro asks, conditional bridge paths, and targets with no warm path (go direct, or fill the gap). It is the ranking layer only: use lead-intelligence (lot 50) for full prospecting pipelines and connections-optimizer (lot 51) for pruning and growing the network. Pure Markdown skill, no code runs on install. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: it needs your actual graph to be useful (X or LinkedIn API access, or lists you paste in); the scores are only as good as the weights you set. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-social-graph-ranker
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-social-graph-ranker
- Category: Social media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/social-graph-ranker/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

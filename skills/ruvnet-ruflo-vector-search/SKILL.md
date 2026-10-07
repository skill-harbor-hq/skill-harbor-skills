<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ruvnet-ruflo-vector-search
description: "HNSW vector search with RaBitQ quantization via the Ruflo MCP plugin — corpus search, quantized..."
---

# Ruflo Vector Search

Honest caveats: **requires the Ruflo MCP plugin installed and configured in your agent** — the skill is an instruction layer over the plugin's `mcp__plugin_ruflo-core_ruflo__*` tools and does nothing without it; pick the right path for your scale (corpus search vs hot-path router — they are not interchangeable). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/ruvnet-ruflo-vector-search
- Fiche en français: https://theskillharbor.com/fr/products/ruvnet-ruflo-vector-search
- Category: Search
- Price: Free
- Verification: unverified
- Source repo: https://github.com/ruvnet/ruflo/blob/main/plugins/ruflo-agentdb/skills/vector-search/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

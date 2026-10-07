<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: 3pm-baking-wright-wright-recipes
description: "Turn recipe web pages into scaled shopping lists, costs and nutrition — 💳 Paid API required"
---

# Wright Recipes

💳 Paid API required — Curated by Skill Harbor — a recipe-operations skill built on the `wright-core` Python library: it parses a recipe web page into a validated structured `Recipe`, then deterministically scales servings, consolidates multiple recipes into one shopping list (merging ingredient variants like kosher/table salt), costs recipes against your purchase history, detects allergens and dietary badges, and analyzes nutrition. Design principle: extraction is probabilistic (LLM), planning is deterministic (testable library code) — the boundary between the two is where you review. Discovered via skills.sh, listed here with credit to its creator by @3pm-baking. Honest caveats: 💳 the `parse` step needs your own LLM API key (OpenAI, Anthropic or Gemini) — scaling, shopping lists and costing run free and locally; drives the CLI via `uvx` (Python + network to fetch the page); does not discover recipes on its own — supply URLs or confirm candidates first. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/3pm-baking-wright-wright-recipes
- Fiche en français: https://theskillharbor.com/fr/products/3pm-baking-wright-wright-recipes
- Category: Food & Drink
- Price: Free
- Verification: unverified
- Source repo: https://github.com/3pm-baking/wright

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

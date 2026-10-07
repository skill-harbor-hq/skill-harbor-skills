<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-cost-aware-llm-pipeline
description: "Keep LLM API spend under control with model routing, immutable cost tracking, narrow retries, and..."
---

# Cost-Aware LLM Pipeline

Curated by Skill Harbor: composable patterns for controlling LLM API costs while keeping quality. Four techniques: model routing by task complexity (cheap models for simple tasks, top tier for complex ones, with threshold examples), immutable cost tracking (frozen dataclasses, cumulative spend, budget limit that fails fast), narrow retry logic (retry only transient errors like rate limits and 5xx, fail immediately on auth or bad-request errors), and prompt caching for long system prompts. A composition section shows all four wired into a single pipeline function, plus a 2026 pricing reference table across model tiers, best practices (start cheap, log routing decisions, set explicit budgets), and anti-patterns (most expensive model for everything, retrying permanent errors, mutating cost state, ignoring caching). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: developer-oriented Python patterns to adapt to your own stack; the pricing table is a 2026 snapshot, always verify current provider pricing before budgeting. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-cost-aware-llm-pipeline
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-cost-aware-llm-pipeline
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/cost-aware-llm-pipeline/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

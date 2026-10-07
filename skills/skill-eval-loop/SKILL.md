<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: skill-eval-loop
description: "Test suites, baselines, staged repairs, approved promotion — for workspace skills."
---

# Skill Eval Loop

A Muse agent skill that evaluates a workspace skill before you trust it: builds a test suite with a baseline and comparison history, applies repairs in stages (one change at a time, with rollback when a change regresses), and promotes the skill only with your approval. Promotion without approval is forbidden, and the skill explains exactly which artifacts you need to ship it. No account, no API key, no network needed.

- Listing: https://theskillharbor.com/products/skill-eval-loop
- Fiche en français: https://theskillharbor.com/fr/products/skill-eval-loop
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Israelmusondaayliffe/muse-skills/tree/main/skills/skill-eval-loop

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

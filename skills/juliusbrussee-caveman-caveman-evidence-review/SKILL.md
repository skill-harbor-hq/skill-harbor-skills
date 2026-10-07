<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: juliusbrussee-caveman-caveman-evidence-review
description: "Read-only audit of Caveman cost evidence — measured list-price cost, Cave Score, traces, latency..."
---

# Caveman Cloud evidence review: where your LLM spend goes

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @juliusbrussee's read-only review workflow for Caveman Cloud evidence — answer "where does the LLM spend go" without ever changing anything. Hard rules: keep measured provider list-price cost, inferred daily headroom, verified ledger savings and evidence cost strictly separate; never fetch payloads (metadata, timing, token counts and status are enough); never supply an organization id; cite trace ids and exact time windows. The workflow: load context (caveman_context or caveman cloud CLI), establish a baseline (caveman_report for overview/costs/score/workflows/verified_savings, caveman_plan for ranked headroom), test the leading explanation against bounded trace searches with a control cohort (never infer causality from one expensive trace), inspect representative traces, and report in a fixed shape — scope, measured cost, verified savings, inferred headroom, findings with trace ids, an "unproven" section, one next read-only check, and a proposal-only possible action. Never start, approve, cancel or roll back an experiment from this skill. Honest caveats: requires a Caveman Cloud account with the caveman CLI/MCP configured and a selected project; the evidence discipline is demanding — empty results mean no signal, not zero cost; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before...

- Listing: https://theskillharbor.com/products/juliusbrussee-caveman-caveman-evidence-review
- Fiche en français: https://theskillharbor.com/fr/products/juliusbrussee-caveman-caveman-evidence-review
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/juliusbrussee/caveman/blob/main/skills/caveman-evidence-review/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

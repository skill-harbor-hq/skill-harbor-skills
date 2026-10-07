<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-continuous-agent-loop
description: "Run self-checking autonomous agent loops with quality gates, evals, and recovery controls."
---

# Continuous Agent Loop

Curated by Skill Harbor: patterns for continuous autonomous agent loops that self-check, gate on evals, and recover from failures. A loop selection flow picks the right shape (strict CI/PR control, RFC decomposition, exploratory parallel generation, or default sequential), and the recommended production stack combines RFC decomposition, quality gates, an eval loop (via the eval-harness skill), and session persistence. Documents the four classic failure modes (loop churn with no measurable progress, repeated retries on the same root cause, merge queue stalls, cost drift from unbounded escalation) and a recovery procedure: freeze the loop, audit the harness, reduce scope to the failing unit, replay with explicit acceptance criteria. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a concise pattern reference, not a runtime; it names sibling ECC skills (ralphinho-rfc-pipeline, plankton-code-quality, nanoclaw-repl) that are separate skills not listed here. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-continuous-agent-loop
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-continuous-agent-loop
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/continuous-agent-loop/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

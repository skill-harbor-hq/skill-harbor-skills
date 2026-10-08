<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-gan-style-harness
description: "Build apps autonomously with a Generator-Evaluator harness: a planner writes the spec, a generator..."
---

# GAN-Style Harness

Curated by Skill Harbor: a GAN-inspired multi-agent harness that separates generation from evaluation, based on Anthropic's March 2026 harness design paper. The core insight is stated plainly: agents asked to evaluate their own work are pathological optimists, but engineering a separate evaluator to be ruthlessly strict is far more tractable than teaching a generator to self-critique. Three agents run the show: the Planner, a deliberately ambitious product manager that expands a one-line prompt into a multi-sprint spec with evaluation criteria; the Generator, a developer that negotiates a sprint contract with the Evaluator before writing code; and the Evaluator, a QA engineer that tests the live running application with Playwright, scoring design quality, originality, craft, and functionality on a weighted rubric with a 7.0 pass threshold, never praising mediocre work. Five to fifteen iterations later, you get the difference Anthropic published: 20 minutes and 9 dollars of solo-agent barely-functional output versus 4 to 6 hours and 125 to 200 dollars of production-ready quality. Configuration runs through environment variables for models, iterations, thresholds, criteria, and eval modes (playwright, screenshot, or code-only). Anti-patterns are documented: lenient evaluators, generators ignoring file-based feedback, infinite loops, superficial evaluator testing, evaluators praising their own fixes, and context exhaustion. The harness even encodes an evolution path: as models...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-gan-style-harness
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-gan-style-harness
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/gan-style-harness/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

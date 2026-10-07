<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-eval-harness
description: "Practice eval-driven development: define capability and regression evals before coding, grade, and..."
---

# Eval Harness

Curated by Skill Harbor: a formal eval-driven development (EDD) framework for AI coding sessions. Evals are the unit tests of AI development: define capability evals (can the agent do something new) and regression evals (did a change break existing behavior) BEFORE implementation, then grade with code-based deterministic graders, model-based LLM-as-judge rubrics, or human review with risk levels. Metrics: pass@k (at least one success in k attempts) and pass^k (all k trials succeed, the higher bar for critical paths), with recommended thresholds (pass@3 >= 0.90 for capability, pass^3 = 1.00 for release-critical regressions). Includes the eval workflow (define, implement, evaluate, report), storage layout (.claude/evals/ definitions, logs, baselines), eval anti-patterns (overfitting prompts to eval examples, happy-path-only measurement, flaky graders in release gates), and best practices (define before coding, deterministic graders first, version evals with code). Note: the skill's example utilities describe a capsule and replay framework where candidate execution is disabled by design (no verified OS containment backend); static checks and receipts are not execution evidence. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a method framework, not an auto-runner; some paths follow Claude Code conventions. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-eval-harness
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-eval-harness
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/eval-harness/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

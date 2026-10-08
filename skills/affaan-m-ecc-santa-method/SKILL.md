<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-santa-method
description: "Multi-agent adversarial verification: two independent reviewers with the same rubric must both pass..."
---

# Santa Method

Curated by Skill Harbor: an adversarial verification framework built on one insight, make a list and check it twice. A single agent reviewing its own output shares the same biases, knowledge gaps, and systematic errors that produced the output; two independent reviewers with no shared context break that failure mode. The architecture runs three phases. Phase 1, make a list: the generator agent produces the deliverable. Phase 2, check it twice: two independent reviewers score the output against the same rubric, blind to each other. Phase 3, naughty or nice: the verdict gate ships the output only if both reviewers pass; otherwise the output goes back for fixes and the loop converges through re-review, with a human escalation cap so the loop cannot spin forever on an unfixable disagreement. Designed for gating publishing, production deploys, compliance or brand-sensitive content, and hallucination-prone claims before they ship. Explicitly not for internal drafts, exploratory research, or tasks with deterministic verification, where build and test pipelines are the right tool. By Ronald Skelton of RapportScore.ai, via the affaan-m/ECC repository (MIT), listed here with credit to its creator. Honest caveats: dual review costs roughly twice the tokens; the rubric is everything, a weak rubric just double-certifies weak output; the escalation cap must be real, or the loop never ends. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-santa-method
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-santa-method
- Category: Quality
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/santa-method/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

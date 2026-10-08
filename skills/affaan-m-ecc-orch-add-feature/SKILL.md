<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-orch-add-feature
description: "Build a brand-new feature end to end with Muse through the shared orch-pipeline engine: research..."
---

# Orchestrated Feature Development

Curated by Skill Harbor: a thin, disciplined wrapper over the shared orch-pipeline engine for the most common orchestration request, adding a capability that does not exist yet. The flow runs the engine with tuned settings: standard size floor (run Research plus Plan unless clearly small), phase mask 0, 1, 2, 4, 5, 6 (Scaffold is MVP-only), and the first move in phase 4 is writing new failing tests for the new behavior before implementing to green. Two hard gates structure the work: Gate 1 requires plan approval before any code, Gate 2 requires confirmation before commit. If the feature touches a security trigger, a security-reviewer is added automatically. The size classifier right-sizes the flow: small or trivial features collapse toward phases 4, 5, 6 instead of running the full ceremony. It differs from the standalone /feature-dev flow by sharing the engine, the size classifier, and both gates with the rest of the orch family, so behavior stays consistent across feature adds, changes, and MVP builds. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this is for net-new behavior only; corrections go to orch-fix-defect and alterations of existing behavior to orch-change-feature. The gates need a human at the keyboard; do not auto-approve them away. The shared engine means the skill's value depends on the orch-pipeline setup in your harness. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-orch-add-feature
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-orch-add-feature
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/orch-add-feature/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

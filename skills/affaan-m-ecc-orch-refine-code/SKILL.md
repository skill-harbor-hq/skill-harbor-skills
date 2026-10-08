<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-orch-refine-code
description: "A behavior-preserving refactor run by the orch engine: confirm tests are green, restructure in..."
---

# Orchestrated Refactoring

Curated by Skill Harbor: a thin, disciplined wrapper over the shared orch-pipeline engine for the one job where the diff must change nothing observable. The rule is absolute: same behavior, better structure. The operation runs a fixed phase mask: plan the restructure, then keep green, with two gates, one on the restructure plan and one pre-commit. The first move is always to confirm the relevant tests exist and are green before touching code; where coverage is thin, characterization tests are added first, because the existing suite is the safety net and no new behavior tests are written. Restructuring proceeds in small steps with the test suite re-run after each. For dead-code and duplication sweeps it delegates to the refactor-cleaner agent, which runs knip, depcheck, and ts-prune and removes safely. The commit lands as refactor:, and the diff must be behavior-neutral. If behavior is meant to change at all, this is the wrong skill; the siblings orch-change-feature and orch-fix-defect cover those. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: green tests prove the suite passes, not that behavior is truly preserved; thin coverage means a thinner safety net, add characterization tests. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-orch-refine-code
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-orch-refine-code
- Category: Refactoring
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/orch-refine-code/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

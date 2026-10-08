<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-orch-pipeline
description: "The shared gated pipeline behind the orch-* family: Research-Plan-TDD-Review-Commit with size..."
---

# Orchestrator Pipeline

Curated by Skill Harbor: the shared orchestration engine behind the orch-* skill family (orch-add-feature, orch-change-feature, orch-fix-defect, orch-refine-code, orch-build-mvp, all already listed here). The orch-* skills are thin wrappers; they do not re-implement any work. They classify the request, choose which phases of this pipeline run, and delegate each phase to an existing ECC agent or command. This file is that pipeline: a gated Research, Plan, TDD implementation, Review, and Commit sequence, with a size classifier that scales ceremony to blast radius (trivial, small, standard, large), an agent and command map per phase, a security-review trigger for sensitive diffs, and two human gates: plan approval before any implementation code, and commit confirmation before any commit. Everything between the gates flows without stopping. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this is a shared reference engine, not a standalone skill. Invoke an operation skill (orch-add-feature, orch-fix-defect, and the others) rather than this engine directly; read this file directly only when adding a new operation to the family or tuning the shared phases, gates, or agent map. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-orch-pipeline
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-orch-pipeline
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/orch-pipeline/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

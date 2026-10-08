<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-orch-build-mvp
description: "Turn a spec document into a working MVP with Muse: thin vertical slices, scaffolded first slice..."
---

# Orchestrated MVP Build

Curated by Skill Harbor: an orchestration recipe that makes Muse bootstrap a working MVP from a design or spec document instead of generating code in one unreviewable blob. The operation starts by reading the spec and extracting scope, locked decisions, and the feature list, then ordering it into thin vertical slices with one end-to-end path first, never all-models-then-all-views. The first slice gets scaffolded, then a generator-evaluator build loop drives each slice against an eval rubric until the score passes or plateaus, writing feedback files per iteration. Two gates keep humans in charge: Gate 1 approves the slice plan, Gate 2 confirms before each commit, with the scaffold and each slice committed as separate feat commits; a security reviewer joins any slice touching a security trigger. The skill is a thin wrapper over the shared orch-pipeline engine, with the GAN harness commands spelled out for the build loop. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: it is designed for the ECC harness, the orch-pipeline engine and GAN commands are separate ECC pieces you need alongside; thin slices are a discipline, the skill will not stop you from ordering a giant slice. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-orch-build-mvp
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-orch-build-mvp
- Category: AI Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/orch-build-mvp/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

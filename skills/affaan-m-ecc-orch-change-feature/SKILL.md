<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-orch-change-feature
description: "Change a working feature to new behavior with Muse: update tests to the new spec first, change the..."
---

# Orchestrated Feature Change

Curated by Skill Harbor: an orchestration recipe that makes Muse change an existing, working feature to new desired behavior without turning the tweak into a regression. The key move is updating the existing tests to express the new desired behavior first, then changing the implementation until they pass; changing the tests first is what separates a tweak from a fix. The skill distinguishes the case from its siblings: not broken, so no bug reproduction ritual; not new, so no greenfield scaffolding, the capability already exists. The plan stays light, with the full planner pass reserved for standard-size changes and up, and research only when the new behavior needs it. Two gates keep humans in charge: Gate 1 approves the plan and the changed tests, Gate 2 confirms before the commit; a security reviewer joins if the change touches a security trigger. The skill is a thin wrapper over the shared orch-pipeline engine. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: it is designed for the ECC harness, you need the orch-pipeline engine alongside; it assumes tests exist to update, without them the tests-first move has nothing to stand on. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-orch-change-feature
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-orch-change-feature
- Category: AI Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/orch-change-feature/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

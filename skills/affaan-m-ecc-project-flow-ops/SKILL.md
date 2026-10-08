<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-project-flow-ops
description: "Backlog triage with Muse across GitHub and Linear: classify PRs as merge, rebuild, close, or park..."
---

# Project Flow Ops

Curated by Skill Harbor: execution-flow operations that make Muse turn disconnected GitHub issues, PRs and Linear tasks into one flow when the problem is coordination, not coding. The operating model is explicit: GitHub is the public and community truth, Linear is the internal execution truth for active scheduled work, and not every GitHub issue needs a Linear issue. Muse reads the public surface first (issue/PR state, author, branch status, review comments, CI status, linked issues), classifies every item into merge, port/rebuild, close or park with a one-paragraph rationale, decides whether Linear is warranted (only when work is active, delegated, scheduled, cross-functional, or important enough to track), and keeps the two systems consistent by posting public resolutions back to GitHub and marking Linear accordingly. Review rules are strict: never merge from title or trust alone, use the full diff; CI red means classify and fix or block, never pretend it is merge-ready; if the real blocker is product direction, say so. Returns a fixed output format: public status, classification, Linear action, and the exact next operator action. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: classification is a recommendation, the merge decision stays yours; it assumes you actually use GitHub and Linear, otherwise half the model does not apply. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-project-flow-ops
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-project-flow-ops
- Category: Project Management
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/project-flow-ops/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

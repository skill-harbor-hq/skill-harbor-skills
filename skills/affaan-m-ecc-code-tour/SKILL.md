<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-code-tour
description: "Generate guided CodeTour walkthroughs anchored to real files and lines: onboarding, architecture..."
---

# Code Tour

Curated by Skill Harbor: a method for creating CodeTour `.tour` files, persona-targeted step-by-step walkthroughs that open directly to real files and line ranges. A good tour is a narrative for a specific reader (a new maintainer, a PR reviewer, someone chasing a production incident), telling them what they are looking at, why it matters, and which path to follow next. The skill defines the tour types (onboarding, architecture, PR-review, RCA/security) and the workflow: discover the repo shape first (README, entry points, folder structure, changed files for PR tours), infer the reader, then write the steps as `.tour` JSON in a `.tours/` directory, never modifying source code as part of the skill. It also says when NOT to use a tour: a one-off explanation is better answered directly, prose docs belong elsewhere, and broad onboarding without a tour artifact is a different skill. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: it produces `.tour` JSON files; to experience them as guided in-editor walkthroughs you need the CodeTour VS Code extension (or compatible viewer). Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-code-tour
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-code-tour
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/code-tour/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

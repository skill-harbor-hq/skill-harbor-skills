<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: trkbt10-indexion-skills-indexion-readme
description: "Init templates, generate per-package READMEs from doc comments, assemble root README via doc.json..."
---

# indexion README construction: template, assemble and verify project READMEs

Curated by Skill Harbor — @trkbt10's indexion-readme: the construction side of README automation for the indexion CLI — initialize template structure and doc.json, generate non-overwriting per-package READMEs from doc comments, assemble the root README from static prose and package entries via doc.json config (or placeholder templates), and verify that edits are purely additive with `plan drift` (cosine-distance guard usable in CI). Documents the asset conventions (config at root or .indexion/readme/, per-package templates, README.mbt.md symlinks), the template syntax, .indexion.toml integration, and known pitfalls — including a candid "known limitation" section where the packages root section currently emits a table instead of rich expansion. Apache-2.0 licensed. Honest notes: the indexion CLI must be installed first — without it the skill is a manual checklist; and template mode auto-creates READMEs in every package it walks, so run it on narrow paths or check git status after. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/trkbt10-indexion-skills-indexion-readme
- Fiche en français: https://theskillharbor.com/fr/products/trkbt10-indexion-skills-indexion-readme
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/trkbt10/indexion-skills/blob/main/skills/indexion-readme/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

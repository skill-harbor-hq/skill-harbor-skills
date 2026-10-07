<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: alwaysmeticulous-skills-meticulous-test
description: "Upload a frontend build once, trigger visual test runs against different bases, then hand off to..."
---

# Meticulous visual testing run for frontend changes

Curated by Skill Harbor — @alwaysmeticulous's skill for running Meticulous visual test runs after implementing a frontend change: Step 1, inspect the CI config (GitHub, GitLab or Bitbucket) to learn what build artifact Meticulous expects; Step 2, upload the build once as a reusable deployment (returns a deploymentId; works with dirty working trees via captured ephemeral commits — untracked files must be git-added first); Step 3, trigger a test run against a base (auto-inferred or explicit) — the same deployment can be re-triggered against different bases without rebuilding; Step 4, hand off the testRunId to the meticulous-review skill, which fetches the diff summary and classifies each visual change as intended or unintended. CLI and MCP command variants are given for every step, plus the gotchas (pass the explicit --testRunId when the tree is dirty, upload-container vs upload-assets modes). Honest caveats: requires a Meticulous account and the CLI (or MCP server) installed and configured — that one-time setup lives in the repo's references/installation.md, outside the AI workflow; this is one half of a two-skill workflow — the companion skills meticulous-cli-update and meticulous-review are not bundled here. ISC licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/alwaysmeticulous-skills-meticulous-test
- Fiche en français: https://theskillharbor.com/fr/products/alwaysmeticulous-skills-meticulous-test
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/alwaysmeticulous/skills/blob/main/skills/meticulous-test/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

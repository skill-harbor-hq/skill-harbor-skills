<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: linear-linear-release-linear-release-setup
description: "Interactive setup for Linear Release tracking — pipeline modeling (stages vs pipelines), CI config..."
---

# Linear Release CI/CD setup assistant

💳 **Paid API required / API payante requise** — Curated by Skill Harbor — Linear's official setup skill for the linear-release CLI: an interactive workflow that models your release pipelines before generating CI configuration. It walks through pipeline-vs-stage modeling with a concrete test (can two things be in-flight at the same time holding different commits? then separate pipelines, not stages), continuous vs scheduled releases, branch models, version sources, monorepo path filters, then generates the config for GitHub Actions (preferring the official action), GitLab CI or CircleCI with copy-paste example templates. Includes the Docker gotchas (glibc only — no Alpine, `git` and `curl` must be installed) and a pre-merge checklist (full clone, one access key per pipeline, correct binary platform, correct branch triggers). By @linear, listed here with credit to its creator. Honest caveats: requires a Linear plan with the Releases feature — paid service, free-tier eligibility unconfirmed; you must create a release pipeline in Linear first — each pipeline has its own access key stored as a CI secret; the skill explicitly defers to the official linear-release README as the source of truth for commands and flags (your agent fetches it at use time rather than trusting the skill's memory); the prebuilt binary needs glibc, so Docker-based CI must avoid Alpine/musl. Discovered via skills.sh. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/linear-linear-release-linear-release-setup
- Fiche en français: https://theskillharbor.com/fr/products/linear-linear-release-linear-release-setup
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/linear/linear-release/blob/main/skills/linear-release-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

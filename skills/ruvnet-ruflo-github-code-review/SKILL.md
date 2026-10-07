<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ruvnet-ruflo-github-code-review
description: "Deploy specialized review agents (security, performance, style, architecture, accessibility) over a..."
---

# GitHub code review — multi-agent swarm review of pull requests

Curated by Skill Harbor — @ruvnet's GitHub code review skill: it initializes a multi-agent review swarm over a pull request — `gh pr view` and `gh pr diff` feed specialized security, performance, style, architecture and accessibility agents, with automated review comments, quality gates and CI/CD integration patterns. Honest caveats: it shells out to `npx ruv-swarm` and expects the gh CLI, ruv-swarm and claude-flow installed — you are running third-party npm packages, so vet those too; it is designed for repos you own or contribute to, and it posts comments under your GitHub identity, so a human read of its output before posting stays wise. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/ruvnet-ruflo-github-code-review
- Fiche en français: https://theskillharbor.com/fr/products/ruvnet-ruflo-github-code-review
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/ruvnet/ruflo/blob/main/.agents/skills/github-code-review/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

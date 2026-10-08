<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-plankton-code-quality
description: "Enforce code quality on every file edit: silent auto-formatting, 20+ linters, Claude-powered fixes..."
---

# Plankton Write-Time Code Quality

Curated by Skill Harbor: an integration reference for Plankton (by @alxfazio), a write-time code quality enforcement system for Claude Code. Every file edit triggers a three-phase PostToolUse hook: silent auto-formatting (ruff format, biome, shfmt and friends fix 40 to 50 percent of issues invisibly), violation collection as structured JSON, then delegation to a claude subprocess that fixes what the agent missed, routing by complexity (Haiku for style, Sonnet for complexity and refactoring, Opus for deep type reasoning) and re-verifying afterward. The main agent only ever sees violations the subprocess could not fix. Plankton also defends against rule-gaming: a PreToolUse hook blocks edits to linter configs, a stop hook catches config changes at session end, and a Bash hook blocks legacy package managers in favor of uv and bun. Setup is manual (install the linters, copy the hooks and configs into your project), it covers Python, TypeScript, Shell, YAML, JSON, TOML, Markdown and Dockerfiles, and it pairs with ECC rather than replacing it. A community contribution to the ECC collection. By @affaan-m, listed here with credit to its creator, Plankton itself by @alxfazio. From the affaan-m/ECC repository (MIT). Honest caveats: installation is manual, review the hook code before installing it; spawning model subprocesses on every edit costs tokens and time, so tune the language gates and timeouts for your project. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-plankton-code-quality
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-plankton-code-quality
- Category: Code Quality
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/plankton-code-quality/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

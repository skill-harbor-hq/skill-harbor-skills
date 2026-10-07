<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: getsentry-skills-commit
description: "Draft Sentry-style conventional commits — type(scope), imperative subject, footers with Fixes/Refs..."
---

# Sentry commit messages: conventional commits with issue references

Curated by Skill Harbor — @getsentry's convention for writing commits, packaged as an agent skill. Before committing, it checks the current branch (creates a feature branch if on main/master unless told otherwise) and commits one coherent, independently reviewable change at a time. Message rules: `<type>(<scope>): <subject>` with imperative present-tense subject (capitalized, ≤70 chars, no trailing period), all lines under 100 chars, body only when useful, never any customer names, emails, secrets or PII. The type set goes beyond classic conventional commits (feat, fix, ref, perf, docs, test, build, ci, chore, style, meta, license, revert) — note `ref` for behavior-free refactoring, `style` for logic-free formatting, `meta` for repo metadata. Footers: `Fixes <issue>` to close, `Refs <issue>` to link, `BREAKING CHANGE:` for breaking changes; commit multi-paragraph messages with separate `-m` flags, never literal `\n` or an interactive editor. Honest caveats: it's a message convention, not tooling — opinionated choices (capitalized subject, `meta` type, the Sentry-specific types) may clash with your own project's commit style. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/getsentry-skills-commit
- Fiche en français: https://theskillharbor.com/fr/products/getsentry-skills-commit
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/getsentry/skills/blob/main/skills/commit/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

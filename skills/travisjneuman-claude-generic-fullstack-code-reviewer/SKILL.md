<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: travisjneuman-claude-generic-fullstack-code-reviewer
description: "Review fullstack code against production standards — NestJS auth guards and DTO validation, Prisma..."
---

# Fullstack code reviewer — Next.js/NestJS review: auth, validation, Prisma, env safety

Curated by Skill Harbor — @travisjneuman's generic-fullstack-code-reviewer skill (from the .claude collection): a pre-commit and PR review playbook for Next.js/NestJS full-stack code against production quality standards. The agent validates by reading the diff — never by running a test/lint/build ladder — and checks backend specifics (NestJS auth guards on protected routes, class-validator DTO input validation, Prisma instead of raw SQL with reversible migrations), frontend specifics (Next.js server vs client component patterns, API route validation, shared types keeping request/response contracts consistent), and cross-stack concerns (.env never committed with placeholders in .env.example, Prisma types regenerated, auth and type contracts aligned), with a quick checklist for completing features, before commits, or reviewing pull requests. It extends a base generic code reviewer (P0/P1/P2 priority system) and points to shared standards for code review, design patterns, and UX principles. Honest caveats: opinionated toward one stack — Next.js 16/NestJS/Prisma assumptions don't transfer to other frameworks; review-by-reading catches logic and security issues but won't replace actually running tests. License: the manifest records MIT (the manifest makes faith); the repo frontmatter carries no license field. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/travisjneuman-claude-generic-fullstack-code-reviewer
- Fiche en français: https://theskillharbor.com/fr/products/travisjneuman-claude-generic-fullstack-code-reviewer
- Category: Dev
- Price: Free
- Verification: unverified
- Source repo: https://github.com/travisjneuman/.claude/blob/main/skills/generic-fullstack-code-reviewer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

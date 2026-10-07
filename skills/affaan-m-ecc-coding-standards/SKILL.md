<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-coding-standards
description: "Baseline code quality for Muse across projects: naming, readability, immutability, KISS/DRY/YAGNI..."
---

# Coding Standards

Curated by Skill Harbor: baseline coding conventions that apply across projects, the shared floor every codebase should meet before framework-specific skills take over. Built on four principles: readability first (code is read more than written), KISS (simplest solution that works, no premature optimization), DRY (extract common logic, no copy-paste), and YAGNI (no speculative generality). Concrete rules with PASS/FAIL pairs across TypeScript and JavaScript: descriptive variable and function names (verb-noun pattern), immutability via spread instead of direct mutation, comprehensive error handling with typed errors, parallel async with Promise.all instead of sequential awaits, real types instead of any, plus React best practices (typed components, custom hooks, functional state updates, no ternary hell), REST API conventions (verbs, consistent response envelopes, zod input validation), file organization and naming, comments that explain WHY not WHAT with JSDoc for public APIs, performance habits (memoization, lazy loading, select only needed columns), testing standards (AAA pattern, descriptive test names), and a code-smell catalog (long functions, deep nesting fixed with early returns, magic numbers replaced by named constants). Knows its scope boundaries: defers to frontend-patterns for React specifics and backend-patterns for API design. Use when starting a new project, reviewing code quality, refactoring toward conventions, setting up linting, or onboarding contributors....

- Listing: https://theskillharbor.com/products/affaan-m-ecc-coding-standards
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-coding-standards
- Category: Code Quality
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/coding-standards/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

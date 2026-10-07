<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: langgenius-dify-backend-code-review
description: "Evidence-first backend reviews — inspect the diff, route to rule packs (DB schema, architecture..."
---

# Backend code review for Dify's api: evidence-first findings with a severity ladder

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @langgenius's backend code review skill, written for the Dify project's own backend (reviews target code under `api/`). The discipline: evidence first — inspect the requested diff or files, read the changed lines plus their behavior owners and nearby tests, trace callers and boundaries only where they decide correctness, and report ONLY findings tied to an observable failure, violated contract, security boundary, data-integrity risk, or demonstrated maintenance problem. Reviews route to bundled rule packs read by diff type: DB schema, architecture, repositories, and SQLAlchemy; when no pack applies, correctness/security/behavior are reviewed directly against local contracts. Findings come on a severity ladder (P0 security/data-loss/outage, P1 user-visible regression or broken auth, P2 concrete correctness defect, P3 minor cleanup only on explicit request), ordered by severity with file:line references, failing contracts and fix directions — no praise sections, no speculative risks. Honest caveats: written for Dify's own repo layout (the `api/` scope and bundled rule packs are Dify-specific) — less useful as a generic reviewer; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/langgenius-dify-backend-code-review
- Fiche en français: https://theskillharbor.com/fr/products/langgenius-dify-backend-code-review
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/langgenius/dify/blob/main/.agents/skills/backend-code-review/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

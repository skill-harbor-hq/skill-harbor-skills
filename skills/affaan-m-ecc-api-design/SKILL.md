<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-api-design
description: "Design consistent REST APIs — resource naming, status codes, pagination, error envelopes..."
---

# REST API design patterns

Curated by Skill Harbor — @affaan-m's REST API design playbook: plural, kebab-case resource naming with URL conventions (including what not to do — verbs in URLs, singular nouns, snake_case), HTTP method semantics with an idempotency table, a status-code reference that maps real failures to the right codes (400/401/403/404/409/422/429, never "200 for everything"), standardized success and error response envelopes (data/meta/links, field-level validation details), offset vs cursor pagination with a when-to-use guide, filtering/sorting/search patterns, token-based auth and resource-level vs role-based authorization examples, rate-limit headers and tier design, URL-path versioning strategy (max two active versions, 6-month deprecation with Sunset headers), plus ready-to-adapt implementation patterns in TypeScript (Next.js + Zod), Python (Django REST Framework) and Go (net/http), and a ship-it checklist. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-api-design
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-api-design
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/.agents/skills/api-design/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

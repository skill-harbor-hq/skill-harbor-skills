<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-documentation-lookup
description: "Fetch current library docs via the Context7 MCP instead of training data: resolve the library ID..."
---

# Documentation Lookup

Curated by Skill Harbor: a small but high-leverage skill that stops your agent from answering library questions from stale training data. When a question depends on a framework or API, the workflow is: call the Context7 MCP's resolve-library-id to get a valid library ID (format /org/project), pick the best match by name and benchmark score, then query-docs for live documentation and code snippets. It activates for setup questions, API references, code examples, or whenever a framework name appears (React, Next.js, Prisma, Supabase, and friends). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: requires the Context7 MCP configured in your harness (Claude Code, Cursor, Codex); without it the workflow has nothing to call; snippet quality follows the benchmark score of the matched library. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-documentation-lookup
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-documentation-lookup
- Category: DevTools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/documentation-lookup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

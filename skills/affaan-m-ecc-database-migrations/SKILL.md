<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-database-migrations
description: "Safe, reversible database migration patterns: forward-only production changes, expand-contract..."
---

# Database Migrations

Curated by Skill Harbor: a database migration skill that treats every schema change like it runs against production, because one day it will. The core principles are strict and practical: every change is a migration (never hand-edit production); production migrations are forward-only, with rollbacks done as new forward migrations; schema and data migrations stay separate, never mixed; and migrations are tested against production-sized data, since a migration that works on 100 rows can lock a table at 10M. It gives concrete PostgreSQL patterns (nullable columns, Postgres 11+ instant defaults, CREATE INDEX CONCURRENTLY, zero-downtime column renames via expand-contract), a pre-apply safety checklist (UP and DOWN present, no full table locks, rollback plan documented), and per-tool workflows for PostgreSQL, Prisma, Drizzle, Kysely, Django, and golang-migrate. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; patterns are starting points, not substitutes for testing against your own data volume; never run a migration on production without a tested rollback plan. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-database-migrations
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-database-migrations
- Category: Databases
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/database-migrations/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-prisma-patterns
description: "Production Prisma ORM patterns for TypeScript: schema design, query optimization, transactions..."
---

# Prisma Patterns

Curated by Skill Harbor: a patterns skill for Prisma ORM that focuses on the non-obvious traps, not just the happy path. It covers ID strategy (cuid vs uuid vs autoincrement), schema defaults with proper indexing, include vs select trade-offs, array vs interactive transaction forms, the PrismaClient singleton pattern, and cursor pagination done right. The anti-patterns section is the real value: updateMany returns a count, not records; the interactive $transaction form times out after 5 seconds; migrate dev can reset your database; manually editing a migration file breaks future deploys with checksum mismatches; @updatedAt silently skips bulk writes; and soft delete plus findUniqueOrThrow leaks deleted records. Serverless connection-pooling guidance included. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; the Prisma API has evolved across major releases, so check your version with npx prisma --version before applying patterns, and never run migrate dev against shared or production databases. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-prisma-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-prisma-patterns
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/prisma-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

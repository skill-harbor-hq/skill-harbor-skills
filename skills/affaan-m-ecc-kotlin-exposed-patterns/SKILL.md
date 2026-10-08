<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-kotlin-exposed-patterns
description: "Database access with JetBrains Exposed: DSL and DAO queries, coroutine-safe transactions, HikariCP..."
---

# Kotlin Exposed ORM Patterns

Curated by Skill Harbor: comprehensive patterns for database access with the JetBrains Exposed ORM. Exposed offers two query styles: DSL for direct SQL-like expressions and DAO for entity lifecycle management. HikariCP manages a pool of reusable database connections configured via HikariConfig; Flyway runs versioned SQL migration scripts at startup to keep the schema in sync; all database operations run inside newSuspendedTransaction blocks for coroutine safety and atomicity. The repository pattern wraps Exposed queries behind an interface so business logic stays decoupled from the data layer and tests can run against an in-memory H2 database. Covers JSON columns, complex queries, setting up database access from scratch, and writing SQL with the DSL or the DAO. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: assumes a Kotlin plus Exposed stack; pooling and migration tuning depend on your database and load. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-kotlin-exposed-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-kotlin-exposed-patterns
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/kotlin-exposed-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

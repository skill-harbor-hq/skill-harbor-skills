<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-postgres-patterns
description: "PostgreSQL for Muse: index cheat sheet (B-tree, GIN, BRIN), composite and partial indexes, RLS..."
---

# PostgreSQL Patterns

Curated by Skill Harbor: PostgreSQL database patterns that make Muse design schemas, pick indexes, and debug slow queries like a DBA. Based on Supabase best practices (credit: Supabase team). Covers the full quick-reference surface: an index cheat sheet mapping query patterns to index types (B-tree for equality and ranges, composite for multi-column filters, GIN for jsonb and full-text search, BRIN for time-series ranges), a data-type quick reference (bigint over int for IDs, text over varchar(255), timestamptz over timestamp, numeric over float for money), and copy-ready patterns for composite index column order (equality columns first, then range columns), covering indexes with INCLUDE, partial indexes for active rows, optimized RLS policies (wrapping auth.uid() in a SELECT), upserts with ON CONFLICT, cursor pagination (O(1) versus OFFSET), and queue processing with FOR UPDATE SKIP LOCKED. Includes anti-pattern detection queries (unindexed foreign keys, slow queries via pg_stat_statements, table bloat) and a configuration template for connection limits, timeouts, monitoring, and security defaults. Use when writing SQL or migrations, designing schemas, troubleshooting slow queries, implementing Row Level Security, or setting up connection pooling. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: configuration values must be tuned to your RAM and workload, they are starting points not gospel; RLS and security...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-postgres-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-postgres-patterns
- Category: Database
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/postgres-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

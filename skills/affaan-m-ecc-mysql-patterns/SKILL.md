<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-mysql-patterns
description: "Production-grade MySQL and MariaDB guidance for Muse: schema defaults, indexing, slow-query triage..."
---

# MySQL & MariaDB Patterns

Curated by Skill Harbor: a production MySQL and MariaDB playbook that makes Muse start every database question with a version check, because the two engines have diverged in SQL details (VALUES(col) deprecated in MySQL but supported in MariaDB, SKIP LOCKED only for queue-style work). Schema defaults are spelled out: BIGINT UNSIGNED AUTO_INCREMENT keys, BINARY(16) for UUIDs, InnoDB, utf8mb4. Indexing covers composite indexes ordered for real query patterns, covering indexes, and when not to index. The slow-query section walks through EXPLAIN interpretation, lock waits, and deadlocks. Transactions cover isolation levels, queue-style consumption, upserts, and optimistic locking. Replication guidance addresses read replicas, lag detection, and failover. Connection pool tuning covers sizing, timeouts, and TLS. Migrations get a review checklist for large production tables where ALTER can lock everything. Keyset pagination, full-text search, JSON columns, and soft deletes all get concrete SQL. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: always verify the engine version before applying a pattern, what works in MySQL 8 may not exist in MariaDB; pool sizing depends on your workload, start conservative. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-mysql-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-mysql-patterns
- Category: MySQL
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/mysql-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

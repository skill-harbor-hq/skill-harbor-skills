<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-jpa-patterns
description: "Model and tune JPA with Muse: entity design, relationships, N+1 prevention, transactions..."
---

# JPA and Hibernate Patterns

Curated by Skill Harbor: a JPA and Hibernate pattern guide that makes Muse design entities and fix data-access performance the way experienced Spring developers do. Entity design covers table mappings with indexes declared up front, auditing with @CreatedDate and @LastModifiedDate, and enum storage as STRING instead of ordinal. Relationships default to lazy loading with JOIN FETCH queries where needed, and the guide is explicit about avoiding EAGER on collections in favor of DTO projections for read paths. Repositories cover derived queries, @Query with Pageable, and interface projections for lightweight reads. Transactions get @Transactional on service methods with readOnly on read paths and a warning against long-running transactions. Pagination covers PageRequest with sorting plus cursor-style id-based paging for large sets. Performance covers composite indexes matching query patterns, batch writes with saveAll and hibernate.jdbc.batch_size, HikariCP pool sizing properties, and cautious second-level cache use with a real eviction strategy. Migrations insist on Flyway or Liquibase, never Hibernate auto DDL in production, with idempotent additive changes. Testing prefers @DataJpaTest with Testcontainers and SQL logging to prove query efficiency. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: Spring Boot focused, so adapt if you run plain Jakarta EE; profiling your own queries beats any generic rule. Skill Harbor...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-jpa-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-jpa-patterns
- Category: JPA
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/jpa-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

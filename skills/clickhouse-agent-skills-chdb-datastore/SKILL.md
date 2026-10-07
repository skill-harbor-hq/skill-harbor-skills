<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: clickhouse-agent-skills-chdb-datastore
description: "Swap import pandas for chdb.datastore to get a lazy ClickHouse-backed DataFrame API with..."
---

# chDB DataStore — ClickHouse-backed pandas, one-line speedup

Curated by Skill Harbor — @clickhouse's skill for teaching agents the chDB DataStore: a lazy, ClickHouse-backed pandas replacement where changing one import line (`import pandas as pd` → `import chdb.datastore as pd`) keeps existing pandas code working unchanged while operations compile to optimized SQL and execute only when results are needed. The skill covers the decision tree (file analysis, cross-source joins, "pandas too slow", raw SQL → use the chdb-sql skill instead), one-pattern connectors for 16+ sources (local files, MySQL, Postgres, S3, ClickHouse Cloud, Iceberg, Delta Lake), the full pandas API (209 supported methods, with `.to_sql()` to inspect generated SQL), the killer feature of joining DataFrames across different sources, and troubleshooting for common setup issues. Apache-2.0 licensed. Honest caveats: requires Python 3.9+ on macOS or Linux (`pip install chdb`) — no Windows; this skill teaches using DataStore, not ClickHouse server administration or raw SQL authoring; example code in the wild embeds plaintext DB credentials, so prefer the secure vault for connection strings. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/clickhouse-agent-skills-chdb-datastore
- Fiche en français: https://theskillharbor.com/fr/products/clickhouse-agent-skills-chdb-datastore
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/clickhouse/agent-skills/blob/main/skills/chdb-datastore/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

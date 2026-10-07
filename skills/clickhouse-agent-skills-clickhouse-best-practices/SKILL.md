<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: clickhouse-agent-skills-clickhouse-best-practices
description: "Official ClickHouse review discipline: 31 impact-prioritized rules with checklists for schemas..."
---

# ClickHouse best practices: 31 rules for schema design, query tuning, ingestion and agent connectivity

Curated by Skill Harbor — the official @clickhouse review discipline for ClickHouse schemas, queries and configurations: 31 rules across 4 categories (schema, query, insert, agent), prioritized by impact, with per-rule files that agents MUST read before answering. Schema reviews check the immutable ORDER BY planning, column cardinality ordering, native types, smallest fitting bitwidth, LowCardinality for string columns, Nullable avoidance, and partition bounds (100–1,000 values); query reviews enforce JOIN algorithm selection, filter-before-join, skipping indices, and ORDER BY-prefix alignment; insert reviews mandate 10K–100K-row batches, async inserts for small high-frequency writes, and ReplacingMergeTree over ALTER UPDATE. Agents also get a connectivity and safety workflow: connect via MCP or CLI, run the 7-step schema discovery (databases → tables → columns → sort keys → skip indexes → sample → EXPLAIN), then execute with LIMITs and timeouts, narrowing filters on timeout or memory errors. Standard output format (Rules Checked → Violations → Compliant → Recommendations) with "Per rule-name..." citations. Honest caveats: an exhaustive rule set — full schema reviews burn a lot of tokens on large estates; the skill assumes the agent can reach a ClickHouse instance (MCP/CLI credentials), which you set up yourself. Apache-2.0. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/clickhouse-agent-skills-clickhouse-best-practices
- Fiche en français: https://theskillharbor.com/fr/products/clickhouse-agent-skills-clickhouse-best-practices
- Category: Database
- Price: Free
- Verification: unverified
- Source repo: https://github.com/clickhouse/agent-skills/blob/main/skills/clickhouse-best-practices/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

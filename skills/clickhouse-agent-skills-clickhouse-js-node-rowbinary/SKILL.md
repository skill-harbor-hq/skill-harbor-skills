<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: clickhouse-agent-skills-clickhouse-js-node-rowbinary
description: "Generates correct-then-fast TypeScript encoders/decoders for the ClickHouse RowBinary wire format..."
---

# ClickHouse RowBinary codec generator for Node.js (readers + writers)

Curated by Skill Harbor — @clickhouse's generator for correct-then-fast TypeScript codecs that read and decode AND write and encode ClickHouse RowBinary streams for the ClickHouse HTTP server (RowBinary, RowBinaryWithNames, RowBinaryWithNamesAndTypes). It starts with the honest question most skills skip — is RowBinary even the right format? (prefer JSON* for string-heavy payloads, Native for columnar analytics) — then applies shared principles in both directions: little-endian DataView access, correct first / specialize later, inlined leaf ops for straight-line row loops, per-column type comments, TypeScript by default, and six worked end-to-end examples with real speedups. Apache-2.0 licensed. Honest notes: Node.js only — no browsers, no Edge; the entry SKILL.md routes you into sibling files (reader.md, writer.md, src/readers, src/writers, EXAMPLES.md), so install the whole folder, not just the entry file. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/clickhouse-agent-skills-clickhouse-js-node-rowbinary
- Fiche en français: https://theskillharbor.com/fr/products/clickhouse-agent-skills-clickhouse-js-node-rowbinary
- Category: Database
- Price: Free
- Verification: unverified
- Source repo: https://github.com/clickhouse/agent-skills/blob/main/skills/clickhouse-js-node-rowbinary/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

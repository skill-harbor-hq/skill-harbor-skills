<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-data-throughput-accelerator
description: "Diagnose and accelerate large data movement (ingestion, backfill, ETL) by isolating the true..."
---

# Data Throughput Accelerator

Curated by Skill Harbor: a skill for when a data pipeline or backfill is too slow and must get faster without losing correctness. It enforces a disciplined method: first separate the candidate bottlenecks (source extraction speed, network transfer, warehouse load speed, transform speed, serving-table freshness, live tail growth), then benchmark variants against each other, then codify the fastest path, always closing with a hard accounting block that proves rows and timestamps cohere. Speed is never the only goal; the goal is faster correct data landing in the right place with proof. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT, declared in frontmatter). Honest caveats: an agent-facing workflow, it expects shell and file tools to run benchmarks; assumes access to the pipeline and its data stores; measure on production-like volumes, toy datasets hide the real bottleneck. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-data-throughput-accelerator
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-data-throughput-accelerator
- Category: Data Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/data-throughput-accelerator/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

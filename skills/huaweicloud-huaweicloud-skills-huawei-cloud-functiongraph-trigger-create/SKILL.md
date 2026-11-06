<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: huaweicloud-huaweicloud-skills-huawei-cloud-functiongraph
description: "Create TIMER and OBS triggers for Huawei Cloud FunctionGraph serverless functions — scheduled..."
---

# Huawei Cloud FunctionGraph: scheduled timer trigger creation

Curated by Skill Harbor — @huaweicloud's official skill for creating TIMER and OBS triggers on Huawei Cloud FunctionGraph: Quartz Cron (and fixed-rate) scheduling via a bundled Python script, plus event-driven OBS triggers that run the function when objects are created or deleted in a bucket (--bucket, --events, optional --prefix/--suffix), a parameter-confirmation checklist, the full Cron expression reference and an OBS event table, verification steps (status, next execution, history; OBS event source in the OBS console), and best practices (UTC timezone, ≥5-min intervals, least-privilege IAM, Cloud Eye alarms; OBS: idempotent functions, never write output back into the watched prefix). Honest caveats: requires a Huawei Cloud account with Access/Secret keys in environment variables, an existing FunctionGraph function, and the FunctionGraph SDK; for OBS triggers, the bucket must already exist in the same region; function executions are billed per invocation (trigger configuration itself is free); max 10 triggers per function; the skill creates triggers only, TIMER and OBS only. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/huaweicloud-huaweicloud-skills-huawei-cloud-functiongraph-trigger-create
- Fiche en français: https://theskillharbor.com/fr/products/huaweicloud-huaweicloud-skills-huawei-cloud-functiongraph-trigger-create
- Category: Cloud
- Price: Free
- Verification: unverified
- Source repo: https://github.com/huaweicloud/huaweicloud-skills/blob/master/skills/computing/functiongraph/huawei-cloud-functiongraph-trigger-create/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: microsoft-azure-quotas
description: "Check and manage Azure quotas across providers and regions — capacity validation, quota increases..."
---

# Azure Quotas — Capacity & Limits Manager

💳 Paid Azure subscription required — Curated by Skill Harbor — Microsoft's quota management skill: quotas are your real deployment capacity, so this skill checks limits and current usage across resource providers and regions with the `az quota` CLI (always CLI first — the REST API's "No Limit" is misleading), compares regional availability to pick deployment targets, submits quota increase requests, and ships ready-made scripts that return limit, usage and available capacity in a single call — including the critical warning that ARM resource types never map 1:1 to quota names. By @microsoft, listed here with credit to its creator. Honest caveats: quota increases are free — you only pay for resources actually used — but some requests need manual review taking hours to days; a few providers (like Cosmos DB) aren't covered by the quota API at all. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/microsoft-azure-quotas
- Fiche en français: https://theskillharbor.com/fr/products/microsoft-azure-quotas
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/microsoft/azure-skills/blob/main/.github/plugins/azure-skills/skills/azure-quotas/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: microsoft-azure-reliability
description: "Assess and improve reliability of Azure Functions and App Service: zone redundancy, ZRS storage..."
---

# Azure Reliability Assessment & Configuration

Honest caveats: only Functions and App Service are supported today (Container Apps is planned, other compute is surfaced but skipped — it refuses to fabricate patches for unsupported services); remediation changes cost money (storage migration, Front Door ~$35/month base, roughly 2× compute for multi-region), and CLI-only changes get overwritten by later IaC deploys. Requires `az login`, Reader access for assessment and Contributor for changes, plus the resource-graph extension. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/microsoft-azure-reliability
- Fiche en français: https://theskillharbor.com/fr/products/microsoft-azure-reliability
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/microsoft/azure-skills/blob/main/.github/plugins/azure-skills/skills/azure-reliability/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: microsoft-azure-airunway-aks-setup
description: "Walk an existing AKS cluster to a running AI model: cluster verification, controller install, GPU..."
---

# AI Runway AKS Setup

Honest caveats: the SKILL.md carries an explicit cost warning — GPU node pools are billable (A100-class nodes run several dollars per hour) and you need a real Azure subscription; it assumes an AKS cluster already exists and hands off to the companion `azure-kubernetes` skill when it doesn't; it uses `kubectl`/`make` directly, no MCP tools. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/microsoft-azure-airunway-aks-setup
- Fiche en français: https://theskillharbor.com/fr/products/microsoft-azure-airunway-aks-setup
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/microsoft/azure-skills/blob/main/.github/plugins/azure-skills/skills/airunway-aks-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

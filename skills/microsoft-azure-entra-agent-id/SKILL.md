<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: microsoft-azure-entra-agent-id
description: "Give each AI agent its own OAuth 2.0 identity: Blueprints, per-instance Agent Identities, token..."
---

# Microsoft Entra Agent ID

Honest caveats: this is admin-grade work — you need one of the Agent Identity Developer, Agent Identity Administrator or Application Administrator Entra roles plus admin consent; Azure CLI tokens are hard-rejected, so credential setup (Federated Identity Credentials in production, client secrets for local dev only) is on you; credentials live on the Blueprint, never on the Agent Identity; and the Graph API shapes evolve, so it leans on Microsoft Learn docs for verification. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/microsoft-azure-entra-agent-id
- Fiche en français: https://theskillharbor.com/fr/products/microsoft-azure-entra-agent-id
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/microsoft/azure-skills/blob/main/.github/plugins/azure-skills/skills/entra-agent-id/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

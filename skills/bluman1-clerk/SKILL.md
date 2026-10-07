<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-clerk
description: "List, create, update, and delete users."
---

# Clerk Connector for Muse

A Muse agent skill that manages users in your Clerk application through the Clerk Backend API: list users, look up one user, create users, update names, and delete users. Creates, updates, and deletes are confirmation-gated (delete is irreversible); reads need no confirmation. Note: request bodies use snake_case field names — never send SDK-style camelCase to this API. Uses a Clerk secret key (`sk_...`, Clerk dashboard > API Keys), kept in Muse's secure vault. Clerk has a free plan. Draft: written from Clerk's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-clerk
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-clerk
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/clerk

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

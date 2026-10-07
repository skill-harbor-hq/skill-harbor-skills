<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-neon
description: "Manage Neon serverless Postgres: projects, branches, databases."
---

# Neon Connector for Muse

A Muse agent skill that manages Neon serverless Postgres infrastructure through the Neon Management API: list projects, inspect one project, list branches, create or delete a branch, and list databases. It manages infrastructure only — SQL queries run over the Postgres wire protocol, so this connector does not run queries. Honest note: branch create and branch delete are HIGH actuations — creating a branch provisions live compute that can incur billable usage, deleting one is irreversible and destroys the branch, its compute endpoint, and its data; both need exact-match confirmation. Connection strings embed database passwords — the CLI masks them on display; never paste a full connection string into chat. Neon has a free tier. Draft: written from Neon's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-neon
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-neon
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/neon

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

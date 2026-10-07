<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-sentry
description: "Triage errors fast — resolve, archive, or assign issues with explicit confirmation."
---

# Sentry Connector for Muse

A Muse agent skill for Sentry error triage: list organizations and projects, list unresolved issues from the last 24 hours sorted by frequency, and resolve, archive, or assign issues. The write commands each need an exact --confirm string echoed by the CLI; reading needs no confirmation. Uses a Sentry auth token (org:read, project:read, event:read — plus event:write for the write commands), kept in Muse's secure vault. Targets sentry.io (US SaaS); EU and self-hosted instances are out of scope. Free tier available. Draft: written from Sentry's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-sentry
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-sentry
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/sentry

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

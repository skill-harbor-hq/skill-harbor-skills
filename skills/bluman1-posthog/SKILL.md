<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-posthog
description: "Read your product analytics — projects and saved insights. Read-only."
---

# PostHog Connector for Muse

A Muse agent skill with read-only access to your PostHog analytics: verify who the key belongs to, list projects, and read saved insights. No insight create/update commands ship. Uses a PostHog personal API key (phx_, scopes query:read and project:read suffice), kept in Muse's secure vault; the API host is configurable (US/EU). Free tier available. Draft: written from PostHog's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-posthog
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-posthog
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/posthog

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

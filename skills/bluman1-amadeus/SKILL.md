<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-amadeus
description: "Search flights and hotels through Amadeus's test and production APIs — search only, this connector..."
---

# Amadeus Travel Search Connector for Muse

A Muse agent skill that searches flights and hotels through Amadeus's APIs. It covers the self-service APIs (flight offers search, hotel search, destination content, locations, and traveler context tools), with sandbox and production environments: the test environment is free, and production includes free call quotas before billing starts. Search-only by design — it never makes bookings or payments, so there is nothing destructive to guard; still, always double-check prices and availability before acting on a result. Uses Amadeus API credentials, kept in Muse's secure vault. Draft: written from Amadeus's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-amadeus
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-amadeus
- Category: Travel
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/amadeus

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

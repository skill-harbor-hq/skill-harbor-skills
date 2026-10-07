<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-oura
description: "Read Oura Ring health data: sleep scores, sleep sessions, readiness, workouts, and SpO2."
---

# Oura Connector for Muse

💳 Paid plan required: this connector needs an Oura Ring with an active paid membership — the listing is free, but the service is billed. See Prerequisites for costs.

A read-only Muse agent skill for your Oura Ring health data: daily sleep scores, detailed sleep sessions, daily readiness, workouts, and SpO2. The Oura API is read-only — zero write risk, nothing to confirmation-gate. Requires an Oura Ring and an active paid membership (some endpoints return 401 without membership). Health data is sensitive: never shared, quoted, or transmitted anywhere except to the user, and never logged outside the session. OAuth 2.0 via a developer app (developer.ouraring.com), token kept in Muse's secure vault. Draft: written from Oura's public API v2 docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-oura
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-oura
- Category: Health
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/oura

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

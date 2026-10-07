<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-google-nest
description: "Read traits and execute commands on Google Nest devices through the Smart Device Management (SDM)..."
---

# Google Nest Connector for Muse

💳 Paid registration required: this connector needs a one-time $5 Google Device Access registration — the listing is free, and the API has no recurring fee. See Prerequisites for costs.

A Muse agent skill that reads traits and executes commands on Google Nest devices through the Smart Device Management API: thermostats (mode, setpoints, ambient readings), cameras and doorbells (events, live-stream generation). Thermostat commands start or stop real HVAC — confirmation-gated (first use per device). Cameras/doorbells expose read-only event traits. Setup: create a Google Cloud project, register it in the Device Access Console (one-time $5 individual registration fee per Google account; no recurring API fee), enable the SDM API, and authorize via OAuth 2.0 — token kept in Muse's secure vault. Draft: written from Google's public SDM API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-google-nest
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-google-nest
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/google-nest

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

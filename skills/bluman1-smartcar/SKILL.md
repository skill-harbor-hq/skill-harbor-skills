<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-smartcar
description: "Read telemetry and send commands to connected cars — lock, unlock, and start are HIGH-risk and..."
---

# Smartcar Vehicle API Connector for Muse

A Muse agent skill that works with Smartcar's vehicle API: odometer and location telemetry, battery/fuel levels, and remote commands (lock, unlock, start/stop charging, remote start where supported). Locking, unlocking, and starting a real car are HIGH-risk by nature — the skill confirms with the user before every command, every time, and reads are always safe. Smartcar offers a usable free tier ($0: 1 connected vehicle, 3 simulated vehicles, no credit card), with Build plans from $1.99/vehicle/app/month for more. Uses Smartcar API credentials, kept in Muse's secure vault. Draft: written from Smartcar's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-smartcar
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-smartcar
- Category: Automotive
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/smartcar

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

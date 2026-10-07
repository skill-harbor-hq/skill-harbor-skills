<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-tesla-fleet-api
description: "Control Tesla vehicles through the official Tesla Fleet API: read live vehicle state, wake a..."
---

# Tesla Fleet API Connector for Muse

💳 Paid API required: this connector needs a paid third-party API — the listing is free, but usage is billed. See Prerequisites for costs.

A Muse agent skill that controls Tesla vehicles through the official Tesla Fleet API: read live vehicle state, wake a sleeping car, and send signed commands. HIGH actuations (lock/unlock, keyless driving) need explicit confirmation on every call, naming the exact physical effect — no standing permission, no exceptions; MEDIUM actuations (charge, sentry/valet, speed limit) confirm on first use per vehicle. Tesla bills pay-per-use (roughly $1 per 1,000 commands, $1 per 500 data requests, $1 per 50 wakes; a $10/month credit covers light individual use) — no free tier; poll sparingly. Heaviest onboarding of the batch: developer app approval needs legal business details, verified domain ownership, and a hosted public key, plus per-vehicle virtual-key pairing. OAuth 2.0, token kept in Muse's secure vault. Draft: written from Tesla's public Fleet API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-tesla-fleet-api
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-tesla-fleet-api
- Category: Automotive
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/tesla-fleet-api

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

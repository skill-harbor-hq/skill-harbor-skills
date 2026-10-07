<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-prusa-connect
description: "Watch and manage Prusa printers from Muse — reads plus G-code upload, with the upload always..."
---

# Prusa Connect Connector for Muse

A Muse agent skill that works with Prusa Connect, the cloud dashboard for Original Prusa printers: printer status, temperatures, print progress, camera snapshots, and G-code file upload. It's mostly a read-and-monitor tool — the one write is G-code upload, and an uploaded file is code the printer will execute, so the skill confirms with the user before every upload and never improvises job commands on its own. Honest caveat from its own SKILL.md: the upload payload is not fully tested against Prusa's docs, so verify the first upload lands correctly before relying on it. Uses Prusa Connect credentials, kept in Muse's secure vault. Draft: written from Prusa's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-prusa-connect
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-prusa-connect
- Category: IoT
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/prusa-connect

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

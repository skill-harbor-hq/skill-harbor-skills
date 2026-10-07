<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-octoprint
description: "Run your OctoPrint server from Muse — print jobs, temperatures, and webcam, with heating and motion..."
---

# OctoPrint 3D Printer Connector for Muse

A Muse agent skill that controls 3D printers through an OctoPrint server: print job lifecycle (start, pause, cancel), hotend and bed temperatures, file uploads, printer profiles, and webcam snapshots. This drives a machine that heats past 200°C and moves physically — any heating, motion, or job-start command is always confirmed with the user before running; never start a print you haven't reviewed the file for. OctoPrint is self-hosted (your own Pi or server) with an API key and optional app-key workflow — keep keys in Muse's secure vault. Draft: written from OctoPrint's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-octoprint
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-octoprint
- Category: IoT
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/octoprint

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

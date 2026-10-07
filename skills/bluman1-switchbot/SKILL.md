<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-switchbot
description: "Flip SwitchBot switches, locks, and curtains from Muse — signature auth handled, home actions..."
---

# SwitchBot Connector for Muse

A Muse agent skill that controls SwitchBot devices through the SwitchBot Cloud API v1.1: bots, plugs, locks, curtains, meters, and scenes. SwitchBot's signature-based authentication (token + secret + nonce + timestamp) is the fiddly part — the skill documents the exact signing steps so you set it up once and forget it. It acts on your physical home — locks, curtains, anything plugged in — so the skill confirms with the user before any write that changes the home's state. The API itself is free to use. Uses your SwitchBot token and secret, kept in Muse's secure vault. Draft: written from SwitchBot's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-switchbot
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-switchbot
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/switchbot

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

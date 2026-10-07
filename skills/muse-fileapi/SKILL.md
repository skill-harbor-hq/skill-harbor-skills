<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: muse-fileapi
description: "Let your Muse read and write your own computer's files — through your own tunnel"
---

# Muse File API

⚠️ Security note from Skill Harbor: this build exposes your local files — and shell commands — to your Muse agent through a tunnel you host yourself. Only expose directories you can afford to share, use your own domain and Cloudflare Tunnel, and never share your token. Understand the setup before going live. Use at your own risk.

A dependency-free local HTTP service, exposed via Cloudflare Tunnel, that lets Muse list, read and write files in whitelisted directories — with two-phase writes and an audit log. You run it on your own machine (Node.js only), expose it through your OWN domain and tunnel, and feed the connector brief to Muse through its secure credential flow. Honest heads-up: the project provides no public endpoint — everything is self-hosted; the README is primarily in Chinese.

- Listing: https://theskillharbor.com/products/muse-fileapi
- Fiche en français: https://theskillharbor.com/fr/products/muse-fileapi
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/star-power0/muse-fileapi

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: amazon-bypass-skill
description: "Search Amazon and add to your cart from Muse, without ever paying."
---

# Amazon Bypass Skill

Amazon Bypass Skill gives Muse a way into Amazon that Amazon's bot blocks can't shut down. A small local API runs on your own PC and drives a real Chromium browser through Playwright, so pages load exactly like they do in front of a human. Search Amazon.ca without logging in. Add items to your cart with session cookies exported from your normal browser. The skill stops there: it never checks out, never pays, and never logs in for you. You review the cart and pay yourself, in your own browser.

Setup takes a Windows PC you can reach over SSH. Install the dependencies with install.ps1, start the server with start.ps1, export your Amazon cookies to the skill's cookies folder, then paste the prompt from MUSE.md into Muse. The server listens only on 127.0.0.1, port 8792, behind a random local API key. Amazon.ca is the default region; us, uk, de, fr and 11 other regions are supported.

- Listing: https://theskillharbor.com/products/amazon-bypass-skill
- Fiche en français: https://theskillharbor.com/fr/products/amazon-bypass-skill
- Category: Productivity
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/house-skills/blob/main/amazon-bypass-skill/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kjames2001-authyouragent
description: "Let your AI agent act for you on websites — you approve everything from your phone."
---

# Auth Your Agent

Curated by Skill Harbor: Auth Your Agent is an open-source MCP server that lets an AI agent act for a person on websites, with the person's approval on their phone. The agent drives a sandboxed browser (the "vault") running on the person's own machine. When a site asks for a password, a CAPTCHA or a 2FA code, the person takes over that browser from their phone, signs in themselves, and hands it back — the agent never sees the password and never holds the cookies. Clicks that submit, send, delete or pay ask the owner's phone first. Secrets (usernames, passwords, authenticator codes) can be filled from the owner's Bitwarden or Vaultwarden: the agent fills them on the right site and field without ever seeing the value. When the task is done, the vault signs out of every site it used, then destroys the browser profile. The MCP server exposes 22 tools (navigate, click, type_text, read_page, request_takeover, request_approval, end_session, and more). By @kjames2001, listed here with credit to its creator. Honest caveats: this is early access software from a brand-new project (created late September 2026) — expect rough edges; the phone app and the approval service run on the creator's hosted service at authyouragent.com, so approval notifications depend on it; the vault runs on your own machine and needs Docker plus Chromium; only public websites open in the vault browser. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kjames2001-authyouragent
- Fiche en français: https://theskillharbor.com/fr/products/kjames2001-authyouragent
- Category: Developer Tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/kjames2001/authyouragent

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

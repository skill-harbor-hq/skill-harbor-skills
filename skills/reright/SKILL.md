<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: reright
description: "Human approval for agent-written text"
---

# Reright

Reright makes your AI agents get your approval before they send text a person will read: commit messages, PR descriptions, emails, support replies. The agent submits a draft with full context (what it's about, who will read it, why it wrote it). You edit it into your own words, approve it, and the agent sends exactly what you approved.

It works through an MCP server plus hooks for Claude Code, Codex, Gemini CLI, Copilot and Cursor, with a global git hook as backstop. Privacy-conscious by design: the hook only sends the SHA-256 hash of the text to check approval, never the text itself.

The command-line client is open source (MIT). The hosted review service has a free plan (10 messages/month); paid tiers start at $5/month.

Honest caveats: only Claude Code has been tested end-to-end; other agents' hooks are built from vendor documentation. The hooks run on your machine and can be bypassed by whoever can edit them. The server is not end-to-end encrypted: interpt operates it and could technically read your drafts.

- Listing: https://theskillharbor.com/products/reright
- Fiche en français: https://theskillharbor.com/fr/products/reright
- Category: Developer tools
- Price: Paid
- Verification: unverified
- Source repo: https://github.com/interpt-co/reright-cli

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

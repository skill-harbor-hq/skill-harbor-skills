<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mcp-skill-harbor
description: "Search the Skill Harbor catalog from inside your Muse — no copy-paste."
---

# Skill Harbor MCP

Skill Harbor MCP connects your Muse (or any MCP-compatible AI assistant) directly to the Skill Harbor catalog. No more copy-pasting between the site and your chat: your assistant searches the directory, reads listings, and fetches install prompts as tools, right inside the conversation.

How it works:

1. Add one URL to your MCP client config: https://theskillharbor.com/mcp. No package to install, no API key, no account.
2. Your assistant gets three tools:
   - search_builds — search 1,800+ AI builds by keywords, in French or English. Same ranking as the site: relevance first, synonyms and singular/plural included.
   - get_build — full details of one build: description, price, seller, verification status, repo link.
   - get_install — the installation prompt, ready to paste into Muse.
3. Just ask: "find me a build that automates invoices" — your assistant searches, summarizes the best matches, and shows you the install prompt for the one you pick.

Privacy: the MCP is read-only and public. It sees only your search keywords — never your files, never your identity, no tracking. Anonymous demand stats (which queries return nothing) feed the public request board, like the site search.

Runs on Skill Harbor's own infrastructure, deployed with the site. If the site is up, the MCP is up.

- Listing: https://theskillharbor.com/products/mcp-skill-harbor
- Fiche en français: https://theskillharbor.com/fr/products/mcp-skill-harbor
- Category: Connectors
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/skill-harbor-mcp

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

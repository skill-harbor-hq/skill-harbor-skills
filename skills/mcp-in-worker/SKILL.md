<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mcp-in-worker
description: "Expose a read-only MCP server inside your Cloudflare Worker: POST /mcp, deploys with the site, no..."
---

# MCP in Worker

MCP in Worker gives AI assistants direct tools into your data without running separate MCP infrastructure. A single POST /mcp endpoint inside your existing Cloudflare Worker speaks MCP over streamable HTTP (JSON-RPC 2.0) and reuses your tested API handlers. It is proven live with three tools, bilingual, and zero auth: search, record detail, and action payload.

The pattern is deliberately small. You define three to five read-only tools with tight JSON schemas: search takes the user's words untranslated (capped at ~120 chars), detail returns the full record, and the action tool returns a copy-paste payload the user confirms elsewhere. Instead of reimplementing search, you synthesize an internal Request to your own tested endpoint and forward the caller's headers, so IP-based rate limits, ranking, synonyms, and logging behave identically.

The worker entry wires three routes before any other handler: POST /mcp is the JSON-RPC dispatcher (initialize, tools/list, tools/call, ping), GET /mcp returns a human-readable info page describing the endpoint and its tools, and OPTIONS /mcp answers the CORS preflight because MCP clients are cross-origin. Tool results are plain text or structured content the model can quote, never HTML.

Operating rules keep it safe: read-only, no tool writes, deletes, or spends. Tool descriptions are self-contained because the calling model never sees your site, only these strings. CORS allows Content-Type, Accept, and Mcp-Session-Id. The endpoint is...

- Listing: https://theskillharbor.com/products/mcp-in-worker
- Fiche en français: https://theskillharbor.com/fr/products/mcp-in-worker
- Category: Connectors
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/house-skills/blob/main/mcp-in-worker/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

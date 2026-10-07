<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-mcp-server-patterns
description: "Build MCP servers with the Node/TypeScript SDK: tools, resources, prompts, Zod validation, and..."
---

# MCP Server Patterns

Curated by Skill Harbor: a patterns skill for building Model Context Protocol servers that AI assistants can actually use. It explains the three primitives (tools as invokable actions, resources as read-only data, prompts as reusable templates), how to register them with the Node/TypeScript SDK, and when to choose stdio transport (local clients like Claude Desktop) versus Streamable HTTP (remote clients like Cursor or cloud). Best practices included: schema-first tool definitions with Zod validation, structured errors the model can interpret, idempotent tools so retries are safe, and SDK version pinning with release-note checks on upgrade. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; the MCP SDK API evolves quickly, so verify method names and signatures against the official MCP docs or Context7 before copying examples, and you need Node.js to build anything. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-mcp-server-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-mcp-server-patterns
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/mcp-server-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

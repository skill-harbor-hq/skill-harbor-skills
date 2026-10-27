<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: n8n-architect
description: "Create, edit, validate, sync, and troubleshoot n8n workflows as TypeScript code, with schema-first..."
---

# n8n Architect

Curated by Skill Harbor: a skill for treating n8n workflows as code instead of clicking them together in a browser. It drives the n8n-as-code command line, n8nac, through a strict operating loop: resolve the workspace from the backend before touching anything, pull a workflow before editing it, author it as a TypeScript file, validate it locally, push it with verification, then test it and present the resulting link. The discipline that holds the whole thing together is schema first. The agent never guesses a node parameter, an operation, or a type version. It looks up exact node schemas, searches bundled examples for a pattern, and only then writes code, which keeps AI-authored workflows aligned with what the connected n8n version actually supports. Sync is handled the same way code is handled: workflow files stay the source of truth in Git, pull and push keep the local files and the remote instance in step, and conflicts have an explicit handling path instead of a silent overwrite. Environments are explicit too: a remote n8n URL with its own API key, or a managed local instance, each bound to its own workflow folder, with credentials passed through stdin and never printed back. An optional native n8n MCP assist can complement the flow for live discovery and execution inspection, but the skill is clear that it does not replace the local command line, the bundled knowledge, the TypeScript files, or Git. By @EtienneLescot, listed here with credit to its creator. Honest...

- Listing: https://theskillharbor.com/products/n8n-architect
- Fiche en français: https://theskillharbor.com/fr/products/n8n-architect
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/EtienneLescot/n8n-as-code/tree/main/skills/n8n-architect

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: imagekit-developer-skills-mcp-preflight
description: "Routing guide for ImageKit's three MCP servers — DAM (media library search/upload/share), Admin..."
---

# ImageKit MCP preflight — pick the right MCP server

Curated by Skill Harbor — @imagekit-developer's MCP preflight skill: a routing guide to be read before any ImageKit MCP call. It maps jobs to the right one of ImageKit's three hosted MCP servers — DAM (`imagekit.io/mcp/dam`) for media library search, upload, organize, tag, share, metadata, collections, path policies, public links and cache purge; Admin for origins/external storage, URL endpoints, and account usage analytics; DevTools for docs search (`search_docs`) and transformation-URL building (`transformation_builder`) — with strict rules (DAM for the media library, Admin for origins/usage — never cross them; never inline file bytes, use signed upload; filter search on the server; search docs before writing integration code). Points to companion skills for search-assets (Lucene queries), upload-files, asset-access-control (file/folder vs collection ACLs), ai-tasks and imagekit-integrations. Honest caveats: DAM and Admin each need a separate connection and ImageKit sign-in (DevTools doesn't) — a missing tool means that server isn't connected or permissioned; the account's free/paid tier is not asserted here. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/imagekit-developer-skills-mcp-preflight
- Fiche en français: https://theskillharbor.com/fr/products/imagekit-developer-skills-mcp-preflight
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/imagekit-developer/skills/blob/main/skills/mcp-preflight/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

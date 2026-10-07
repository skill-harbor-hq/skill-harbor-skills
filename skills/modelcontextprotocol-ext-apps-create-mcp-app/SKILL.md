<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: modelcontextprotocol-ext-apps-create-mcp-app
description: "Build MCP Apps — an MCP tool plus a bundled HTML resource with lifecycle handlers, framework..."
---

# Create MCP App: build interactive UIs inside MCP-enabled hosts (short listing)

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @modelcontextprotocol's official guide for building MCP Apps — interactive UIs that run inside MCP-enabled hosts like Claude Desktop. The core concept: every MCP App is a tool plus an HTML resource, linked by the tool's `_meta.ui.resourceUri` — the host calls the tool, renders the resource UI, the server returns the result, and the UI receives it. Covers framework selection (React with a `useApp` hook, vanilla JS, Vue/Svelte/Preact/Solid with manual lifecycle), project setup for existing or new MCP servers, framework templates to clone from the SDK repo, API references (App class handlers, server registration helpers, spec types, theming), and advanced patterns: app-only tools, polling dashboards, chunked responses, binary resources, network requests with CSP configuration, host context (theme, fonts, safe areas), fullscreen mode, streaming input, view-state recovery, plus common mistakes (missing text fallback, CSP misconfiguration, handlers registered after connect) and local testing with the basic-host example. Honest caveats: you'll build against a live SDK — the guide expects you to clone the SDK repo for examples and JSDoc, and to bundle UIs with vite-plugin-singlefile; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/modelcontextprotocol-ext-apps-create-mcp-app
- Fiche en français: https://theskillharbor.com/fr/products/modelcontextprotocol-ext-apps-create-mcp-app
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/modelcontextprotocol/ext-apps/blob/main/plugins/mcp-apps/skills/create-mcp-app/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

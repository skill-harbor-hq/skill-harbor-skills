<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ueberdosis-tiptap-tiptap
description: "The official Tiptap team's skill for agents — integrate the headless rich-text editor correctly..."
---

# Tiptap integration: build rich-text editors with AI assistance

Curated by Skill Harbor — @ueberdosis's official tiptap skill (authored by the Tiptap team itself): instructions for coding agents to integrate and work with the Tiptap headless rich-text editor. The core discipline: never guess or invent patterns — ground every decision in the Tiptap docs and source (docs are fetched as Markdown by appending .md to any tiptap.dev/docs URL; llms.txt lists every page; read installed source from node_modules/@tiptap/*; clone only shallowly for demos you can't get otherwise). Best practices: resolve the latest stable version with npm view, pin all monorepo extension packages to one version line (never mix majors, upgrade Tiptap 2 projects first), resolve pro packages from the registry (never from @tiptap/core), set immediatelyRender: false for SSR, default to the Composable API for React. Feature recipes with doc links: real-time collaboration (Y.Doc + Collaboration extension + TiptapCollabProvider with Cloud appId/token), comments, tracked changes, import/export (DOCX, PDF, Markdown), the AI Toolkit (agentic document work, server-side default), basic AI generation, version history, snapshot compare, pages. Honest caveats: real-time collaboration runs on Tiptap Cloud (free tier exists, paid tiers for production scale — get the appId/token from the Cloud dashboard) and some pro extensions come through a private npm registry (see the pro-extensions guide); retired AI extensions (AI Agent, AI Changes, AI Suggestion, AI Assistant) must not be...

- Listing: https://theskillharbor.com/products/ueberdosis-tiptap-tiptap
- Fiche en français: https://theskillharbor.com/fr/products/ueberdosis-tiptap-tiptap
- Category: Frontend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/ueberdosis/tiptap/blob/main/skills/tiptap/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

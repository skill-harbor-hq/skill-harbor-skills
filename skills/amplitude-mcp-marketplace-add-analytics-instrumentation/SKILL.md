<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: amplitude-mcp-marketplace-add-analytics-instrumentation
description: "End-to-end analytics instrumentation workflow — reads the code, discovers trackable events, and..."
---

# Analytics instrumentation pipeline for a PR, branch or feature

Honest caveats: an orchestrator, not a solo skill — the full pipeline needs its sibling skills (`diff-intake`, `discover-event-surfaces`, `instrument-events`) installed too; connecting the Amplitude MCP server unlocks the live taxonomy/catalog reads; it produces a tracking plan for your review, it does not write the instrumentation code itself. Discovered via skills.sh. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/amplitude-mcp-marketplace-add-analytics-instrumentation
- Fiche en français: https://theskillharbor.com/fr/products/amplitude-mcp-marketplace-add-analytics-instrumentation
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/amplitude/mcp-marketplace/blob/main/plugins/amplitude/skills/add-analytics-instrumentation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: amplitude-mcp-marketplace-instrument-events
description: "Turn event candidates into a line-by-line Amplitude tracking plan with per-event app-id routing"
---

# Amplitude analytics instrumentation planner

Curated by Skill Harbor — @amplitude's own skill for step 3 of their analytics instrumentation workflow: it takes `event_candidates` YAML (produced by their discover-event-surfaces skill), filters to priority-3 critical events, reads repo conventions (`.amplitude/instrumentation-agent-context.md`) and the path→app-id mapping (`.amplitude/instrumentation-agent.yaml`), inspects the hinted files to find the exact insertion point and in-scope variables for each tracking call, designs minimal chart-useful properties (2–4 per event), and outputs a structured JSON tracking plan — with explicit confirmation before anything is written back to Amplitude via MCP. Honest caveats: requires an Amplitude account (a free plan exists) plus the Amplitude MCP integration; works best on the output of the sibling discover-event-surfaces skill; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/amplitude-mcp-marketplace-instrument-events
- Fiche en français: https://theskillharbor.com/fr/products/amplitude-mcp-marketplace-instrument-events
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/amplitude/mcp-marketplace/blob/main/plugins/amplitude/skills/instrument-events/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

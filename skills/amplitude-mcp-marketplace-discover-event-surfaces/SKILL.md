<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: amplitude-mcp-marketplace-discover-event-surfaces
description: "Read a change brief and generate an exhaustive, prioritized list of analytics event candidates for..."
---

# Discover event surfaces: analytics instrumentation planner

Curated by Skill Harbor — @amplitude's official analytics instrumentation planner: feed it a `change_brief` YAML (produced by its sibling `diff-intake` skill) and it maps user flows, builds funnel hypotheses, pulls your existing Amplitude taxonomy, then generates an exhaustive list of candidate analytics events — named consistently, categorized (business outcome, user journey, feature success, friction/failure), quality-filtered, deduplicated against what you already track, and prioritized 1-3 for release-criticality. Honest caveats: it is step 2 of a two-skill workflow and assumes the `change_brief` input format; requires an Amplitude project connected via MCP and familiarity with your codebase for the funnel-mapping pass. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/amplitude-mcp-marketplace-discover-event-surfaces
- Fiche en français: https://theskillharbor.com/fr/products/amplitude-mcp-marketplace-discover-event-surfaces
- Category: Marketing
- Price: Free
- Verification: unverified
- Source repo: https://github.com/amplitude/mcp-marketplace/blob/main/plugins/amplitude/skills/discover-event-surfaces/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

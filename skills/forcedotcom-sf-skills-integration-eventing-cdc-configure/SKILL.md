<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: forcedotcom-sf-skills-integration-eventing-cdc-configure
description: "Generate valid CDC metadata (PlatformEventChannelMember/PlatformEventChannel) for subscribing..."
---

# Salesforce Change Data Capture — channel and metadata generator

Curated by Skill Harbor — @forcedotcom's official skill for wiring Salesforce Change Data Capture without memorizing metadata quirks. The agent generates only the two metadata types CDC actually accepts — `PlatformEventChannelMember` per subscribed (entity, channel) pair and `PlatformEventChannel` for custom channels — translating source objects to ChangeEvent entity names, deriving valid custom channel developer names (`__chn` suffix), adding enrichment fields and SOQL-style filter expressions, and steering clear of the many documented deploy landmines (single-underscore filenames, no `data/` channel prefix, four-element-only member XML, DateTime filters restricted to equality, no relationship traversals). It asks clarifying questions when the entity, channel, enrichments or filters are unclear, never runs the deploy itself, and delegates related work (custom objects, fields, permission sets) to sibling skills. Apache-2.0 licensed. Honest caveats: you still need a Salesforce org with the right edition/permissions plus the `sf` CLI to dry-run and deploy; pricing and CDC event limits are explicitly out of scope — check the CDC Developer Guide yourself. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/forcedotcom-sf-skills-integration-eventing-cdc-configure
- Fiche en français: https://theskillharbor.com/fr/products/forcedotcom-sf-skills-integration-eventing-cdc-configure
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/forcedotcom/sf-skills/blob/main/plugins/builder/integration/skills/integration-eventing-cdc-configure/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

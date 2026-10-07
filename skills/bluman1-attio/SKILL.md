<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-attio
description: "Query CRM records, upsert by matching attribute, add notes and tasks."
---

# Attio Connector for Muse

A Muse agent skill that reads and writes your Attio CRM: list objects, query records on any object, create-or-update records with upsert (its preferred write path), and add notes and tasks to records. Reading needs no confirmation; upsert, note, and task are writes — the skill confirms which record is touched and exactly what will be written, unless you grant standing permission. Honest note: Attio's standard API rate limits apply; the skill backs off on 429s. Draft: written from Attio's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-attio
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-attio
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/attio

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

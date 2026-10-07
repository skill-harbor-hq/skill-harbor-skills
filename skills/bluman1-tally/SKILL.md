<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-tally
description: "List forms, read submissions, manage form blocks."
---

# Tally Connector for Muse

A Muse agent skill that works with Tally forms: list forms, fetch one with its full blocks, create a new form, replace a form's blocks, and read submissions. `create` and `update` are writes — confirmed with you first. Honest note: `update` PATCHes the form and replaces the ENTIRE blocks array — the skill always fetches the form first and edits the fetched blocks, because skipping that step wipes blocks you did not mean to touch. The Tally API is free on all plans. Draft: written from Tally's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-tally
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-tally
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/tally

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

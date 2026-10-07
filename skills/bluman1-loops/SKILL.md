<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-loops
description: "Manage email contacts, trigger automations, send transactional email."
---

# Loops Connector for Muse

A Muse agent skill that manages Loops email contacts and trigger sends: look up a contact by email, keep contacts current with create/upsert, fire custom events for automations, and send transactional emails from a template. Sending a real email is a write — the skill confirms the recipient and payload first, and double-checks the template id. Reading needs no confirmation. Honest note: Loops keys are per account — a key from one Loops account cannot touch another. Loops has a free tier. Draft: written from Loops's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-loops
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-loops
- Category: Communication
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/loops

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

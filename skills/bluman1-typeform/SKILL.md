<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-typeform
description: "Read forms and responses, manage webhooks, create forms — writes need confirmation."
---

# Typeform Connector for Muse

A Muse agent skill for the Typeform API: list forms, fetch a form and its fields, list responses with answers, and manage response webhooks. Webhook create/delete and form creation each need an exact-match confirmation every time — creating a webhook starts delivering respondent data, and creating a form publishes a live form. Reading needs no confirmation. Uses a Typeform personal access token, kept in Muse's secure vault. Honest note: webhook paths and the create-form body shape come from Typeform's public docs and are not yet verified live. Draft: not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-typeform
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-typeform
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/typeform

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

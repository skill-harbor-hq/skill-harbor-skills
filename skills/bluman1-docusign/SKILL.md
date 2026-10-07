<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-docusign
description: "Draft and send signature envelopes (demo environment by default), check envelope status, and..."
---

# DocuSign Connector for Muse

💳 Paid API required: this connector needs a paid third-party API — the listing is free, but usage is billed. See Prerequisites for costs.

A Muse agent skill that works with DocuSign's eSignature REST API v2.1: list envelopes, fetch envelope details and recipient status, prepare DRAFT envelopes, send a draft envelope to signers, and download envelope documents. Demo is the default (`demo.docusign.net` sends no legally effective documents) and is mandatory for testing — never run a first-time flow against production. Sending is HIGH and has legal effect: it requires exact confirmation naming the legal effect, on every call, in demo and in production. Production use requires a paid DocuSign plan. Uses OAuth 2.0 (integration key registered in DocuSign Apps and Keys), kept in Muse's secure vault. Draft: written from DocuSign's public eSignature REST API v2.1 docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-docusign
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-docusign
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/docusign

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

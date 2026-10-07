<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-huggingface
description: "Verify your Hugging Face account and search the model hub. Read-only."
---

# Hugging Face Connector for Muse

A Muse agent skill that verifies your Hugging Face account (whoami: name, email, account type) and searches the public model hub by keyword, with likes and download counts. Read-only by design — no repository creation, upload, or delete commands ship. Uses a Hugging Face user access token (a fine-grained read token is enough), kept in Muse's secure vault. Draft: written from Hugging Face's public Hub API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-huggingface
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-huggingface
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/huggingface

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

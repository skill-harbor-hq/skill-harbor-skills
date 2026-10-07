<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-flyio
description: "List apps and machines, manage machine lifecycle, run exec commands."
---

# Fly.io Connector for Muse

A Muse agent skill that manages your Fly.io Machines through the Machines REST API: list apps and machines, inspect machines and volumes, create machines, stop/start/restart them, and run one-off commands inside a machine with exec. Reading needs no confirmation; machine create/stop/start/restart are writes — the skill confirms the exact action on the exact machine first, and exec is confirmation-gated with an explicit warning (never destructive without you seeing the exact command). Honest note: creating machines incurs Fly.io usage costs; Fly.io includes free allowances. Draft: written from Fly.io's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-flyio
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-flyio
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/flyio

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

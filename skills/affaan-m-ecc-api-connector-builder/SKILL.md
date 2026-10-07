<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-api-connector-builder
description: "Add a new API integration that matches the repo's existing connector style instead of inventing a..."
---

# API Connector Builder

Curated by Skill Harbor: a method for adding one more integration to a codebase without inventing a second architecture. The skill starts from the host repository's own habits: it inspects at least two existing connectors to map the file layout, config schema, auth model, retry and pagination conventions, error handling, registry wiring, and test style, then defines only the integration surface the repo actually needs (auth flow, key entities, core read/write operations, rate limits, webhook or polling model). The build follows repo-native slices (config, client/transport, mapping layer, provider entrypoint, registration, tests) with a quality checklist, and the guardrails push back against the two classic failure modes: inventing a new integration architecture when the repo already has one, and cargo-culting an outdated connector when a newer pattern exists. Reference shapes are given for provider-style (Python), connector-style, and TypeScript plugin layouts, plus related skills for backend patterns and MCP servers. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; it assumes the target repo already has connectors to learn from, otherwise there is no house style to match. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-api-connector-builder
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-api-connector-builder
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/api-connector-builder/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: prisma-compute
description: "Prisma Compute deployment guide — Composer 2.0.0, module.ts, prisma deploy/dev, stages, service logs"
---

# Prisma Compute Deployment Guide

Honest caveats: deploy commands exist only in the Prisma 8 CLI (in a Prisma 6 or 7 project, `npx prisma` runs that version's ORM CLI, which has none of these commands); the CLI moves fast — verify command syntax with `--help` first (the skill insists on it); credentials some commands print once (`postgres create`, `bucket key create`) must be stored, never echoed; and deploys do not build your app, so build first. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/prisma-compute
- Fiche en français: https://theskillharbor.com/fr/products/prisma-compute
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/prisma/skills/blob/main/prisma-compute/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

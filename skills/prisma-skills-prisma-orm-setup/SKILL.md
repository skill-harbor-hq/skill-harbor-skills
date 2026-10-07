<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: prisma-skills-prisma-orm-setup
description: "Official Prisma skill that detects your Prisma 6/7/8 starting point, bootstraps new Prisma 8 apps..."
---

# Prisma ORM setup — version-aware install and connection repair

Curated by Skill Harbor — Prisma's official ORM setup skill: it detects your starting point (new app vs existing Prisma 6, 7 or 8 — the CLI version alone doesn't identify the app version, so it inspects `@prisma/client` and the schema), bootstraps new applications on Prisma ORM 8 with a pinned CLI release, keeps existing apps on their major with per-provider references (PostgreSQL, MySQL, SQLite, SQL Server, CockroachDB, MongoDB, Prisma Postgres), runs `prisma skills sync` to load the package-owned prisma-8 guidance, and verifies with a real read-only query. Honest caveats: a real database (paid or self-hosted) is needed for live verification; the skill is the setup router — deep Prisma 8 configuration lives in the companion prisma-8 skill. Sibling Prisma skills (prisma-cli, prisma-postgres-setup, prisma-client-api and others) are already listed here. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/prisma-skills-prisma-orm-setup
- Fiche en français: https://theskillharbor.com/fr/products/prisma-skills-prisma-orm-setup
- Category: Database
- Price: Free
- Verification: unverified
- Source repo: https://github.com/prisma/skills/blob/main/prisma-orm-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

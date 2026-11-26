<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: prisma-postgres-setup
description: "Obtain or reuse a Prisma Postgres database and connect an application: provisioning, wiring..."
---

# Prisma Postgres Setup

Curated by Skill Harbor: the Prisma team's workflow for obtaining or reusing a Prisma Postgres database and connecting an application: inspect the project first (requested ORM or driver, installed packages, connection state), then reuse an existing database or provision one: native integration flows for v0 and the Vercel Marketplace, or an authenticated CLI / MCP tool / Console / Management API for standalone persistent databases, or a temporary `create-db` database with expiry for development. Connecting the app means storing the connection string in the project's secret environment configuration, never in source code or chat, preserving unrelated entries, and accounting for the fact that the app and the shell may load different env files (a variable missing from the shell does not mean the database is missing). ORM configuration is then handed to the separate `prisma-orm-setup` skill, which owns version selection, and setup closes with a read-only verification query against the intended database through the app's chosen ORM or driver. By @prisma, listed here with credit to its creator. Honest caveats: this skill deliberately stops at database provisioning: if you need full ORM setup, the `prisma-orm-setup` skill is required and must be loaded separately; it honors explicit alternative choices (Drizzle, `pg`, database-only), and it never prints credentials while checking secret presence. Skill Harbor never reviews the code, review it yourself before use.

Changed November...

- Listing: https://theskillharbor.com/products/prisma-postgres-setup
- Fiche en français: https://theskillharbor.com/fr/products/prisma-postgres-setup
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/prisma/skills/blob/main/prisma-postgres-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

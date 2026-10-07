<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: aeonbridge-ab-anthropic-claude-skills-evolution-api
description: "Build WhatsApp integrations and automations with Evolution API: Docker/Node deployment, instance..."
---

# Evolution API — self-hosted WhatsApp integration platform

Curated by Skill Harbor — @aeonbridge's evolution-api skill, listed here with credit to its creator: an expert guide to Evolution API, the open-source self-hosted WhatsApp integration platform. It covers deployment (Docker Compose with PostgreSQL/Redis, NVM, or PM2), full configuration (server, authentication, database, webhooks, per-integration flags for Typebot, Chatwoot, OpenAI, Dify, RabbitMQ, SQS, S3/MinIO), instance lifecycle (create, QR-code pairing, connection state, restart/logout/delete), the complete REST surface (text/media/location/contact/list/button messages, groups, contacts and profiles, webhooks, Typebot/Chatwoot/OpenAI/Dify integrations), webhook handlers in Node.js and Python, production practices (security, high availability, monitoring, backups, rate limiting), troubleshooting recipes, and migration notes from WhatsApp Web.js and Baileys. Honest caveats: the WhatsApp connection goes through Baileys, an unofficial channel — it can break when WhatsApp changes things and it carries a real account-ban risk, so use a dedicated number, never your main one; Evolution API itself ships under Apache-2.0 with branding-notification requirements (noted in the skill body), while this skill is listed MIT per the discovery manifest; self-hosting means you own the ops burden (TLS, secrets, backups). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/aeonbridge-ab-anthropic-claude-skills-evolution-api
- Fiche en français: https://theskillharbor.com/fr/products/aeonbridge-ab-anthropic-claude-skills-evolution-api
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aeonbridge/ab-anthropic-claude-skills/blob/main/output/evolution-api/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

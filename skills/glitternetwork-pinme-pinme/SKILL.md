<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: glitternetwork-pinme-pinme
description: "Deploy without config — upload static files to IPFS, or scaffold and ship full-stack projects..."
---

# PinMe — zero-config IPFS uploads and full-stack deploys

Curated by Skill Harbor — @glitternetwork's PinMe skill: zero-config deployment driven by the `pinme` CLI. Two paths — Path 1 uploads files or static sites to IPFS (`pinme upload ./dist`, optional subdomain binding, CAR import/export, upload history); Path 2 scaffolds full-stack projects (React+Vite frontend on IPFS, Cloudflare Worker backend at `{name}.pinme.pro`, D1 SQLite database, project R2 bucket) with single-command deploys (`pinme save` for everything, `update-worker`/`update-web`/`update-db` for targeted updates), worker code patterns (CORS, JSON APIs, parameterized D1 queries, email sending via the PinMe platform API), SQLite migration conventions, and a strict never-upload list (`node_modules/`, `.env`, `.git`, sources). Honest caveats: requires a PinMe account — login or `pinme set-appkey <AppKey>` before any upload or deploy; the agent always returns the full final URL including hash fragments, never truncated. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/glitternetwork-pinme-pinme
- Fiche en français: https://theskillharbor.com/fr/products/glitternetwork-pinme-pinme
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/glitternetwork/pinme/blob/main/skills/pinme/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: glitternetwork-pinme-pinme-share
description: "Turn a result into a polished static share artifact — project link, Codex conversation summary..."
---

# PinMe Share — polished share pages for results

Curated by Skill Harbor — @glitternetwork's PinMe Share skill: the publishing companion to the main `pinme` skill. It turns a finished result into a polished static share artifact — a share page wrapping a deployed project link, a Codex conversation summary (decisions, work done, files changed, follow-ups), or a report/file/demo — built as a single self-contained `index.html` with inline CSS, clean responsive design, and semantic accessible HTML. Enforces sanitization before publishing: strip secrets, tokens, API keys, `.env` values, internal-only URLs, private user data and raw transcripts (summarize instead unless verbatim sharing is explicitly approved), then `pinme upload share/<slug>` and return the full URL. Honest caveats: requires PinMe authentication (login or AppKey); if the task needs a backend, database, auth or email, use the main `pinme` skill first and `pinme-share` last. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/glitternetwork-pinme-pinme-share
- Fiche en français: https://theskillharbor.com/fr/products/glitternetwork-pinme-pinme-share
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/glitternetwork/pinme/blob/main/skills/pinme-share/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

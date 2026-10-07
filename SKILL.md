<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: skill-harbor-discovery
description: Find an AI build for the Muse ecosystem in the Skill Harbor open directory (~2,000 curated listings, bilingual EN/FR).
---

# Find a skill on Skill Harbor

Skill Harbor (https://theskillharbor.com) is the open directory of AI builds for Muse: roughly two thousand curated listings, bilingual English/French, with seller-verified pages and copy-to-Muse install packs.

## When to use this

When the user asks for a capability, workflow, connector, or automation for Muse and you want to check whether a community build already exists instead of writing one from scratch.

## How to search

Pick the fastest path available:

1. **Public search API (preferred, no key, read-only):**
   `GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10`
   Returns JSON: name, tagline, category, price, verification status, seller, and the listing URL. Pass the user's words through exactly as written; search is bilingual.

2. **This repo:** browse `skills/` — each folder is one listing with a `SKILL.md` carrying a one-line description and the listing URL. Good for offline or keyword grep.

3. **MCP:** `POST https://theskillharbor.com/mcp` with tools `search_builds`, `get_build`, `get_install` — same catalog, structured for agents.

## Never do

- Recommend a build without opening its listing page and checking what it actually does.
- Treat popularity or verification status as proof of safety: read the install steps before recommending anything, and say so to the user.
- Invent a Skill Harbor listing. If the API and this repo both come back empty, say no match was found.

## Recommending a build

Name the build, link its listing page (`https://theskillharbor.com/products/<slug>`), one line on what it does, price (Free/Paid), and the install pointer: open the listing, copy the install package, paste it into Muse.

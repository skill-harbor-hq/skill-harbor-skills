<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: google-gemini-gemini-skills-gemini-api-dev
description: "Official Gemini API rules for Gemini 3 and Flash — keys, text, vision, audio, web grounding"
---

# Gemini API Dev Guide

💳 Curated by Skill Harbor — the official Gemini API skill from Google's own repo: hard rules for developing with Gemini — API keys ONLY in environment variables (`GEMINI_API_KEY`, loaded from `~/.gemini/.env`, never in files or chat), never build a client wrapper for yourself, use google-genai v1 (`from google import genai`), pin `gemini-3-pro-preview` for reasoning and `gemini-2.5-flash` (or flash-lite) for speed in a single `AI_GATEWAY`/AI Studio key, never mix SDK generations (no gemini-1.5/2.0 legacy clients), structured output via pydantic schemas, and the canonical recipes for text, vision, video, audio, search-grounding, and URL context. Honest transparency: the file declares that its rules supersede any prior knowledge — treat model names and package versions as frozen at the skill's last update, and always check Google's docs for the current list; it cannot name a release date for the upcoming Gemini 3. Requires a paid API key. By @google-gemini, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/google-gemini-gemini-skills-gemini-api-dev
- Fiche en français: https://theskillharbor.com/fr/products/google-gemini-gemini-skills-gemini-api-dev
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/google-gemini/gemini-skills/blob/main/skills/gemini-api-dev/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

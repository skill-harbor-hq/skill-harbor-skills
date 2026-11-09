<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bitwize-music-studio-claude-ai-music-skills
description: "Write lyrics and Suno prompts for a full album, from concept to promo."
---

# Bitwize Music Skills for Muse

Bitwize Music Skills is a 53-skill plugin that walks Muse through making an album, end to end: concept, lyrics, Suno prompts, mixing, mastering and promotion. The lyric-writer and suno-engineer skills are current (Suno v6, v6-wild, v6-mini). A local MCP server adds 91 tools for lyrics, Suno, mastering, mix and promo.

Sandbox test, 2026-11-08: double install, identical both times; manifest and 53 skills valid; the MCP server boots in 3.6 s and lists 91 tools; the repo's light test subset passes (273 passed) once the plugin's Python dependencies are installed.

Caveats:
- The MCP server needs the plugin's full Python dependencies (`requirements.txt`, Python 3.11+, scipy included, tens of MB). It does not start on `mcp[cli]` alone.
- The `db_*` and cloud tools need their own setup (Postgres, S3) and do nothing without it.
- PostToolUse hooks run on every Write/Edit (read-only validators, no network).
- Real Suno generation was **not tested** (account + credits required), nor the full test suite (165 files), the DB/cloud tools, or end-to-end mastering and mixing.

- Listing: https://theskillharbor.com/products/bitwize-music-studio-claude-ai-music-skills
- Fiche en français: https://theskillharbor.com/fr/products/bitwize-music-studio-claude-ai-music-skills
- Category: Audio
- Price: Free
- Verification: verified
- Source repo: https://github.com/bitwize-music-studio/claude-ai-music-skills

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

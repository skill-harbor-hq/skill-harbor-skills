<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-playht
description: "Text-to-speech, voices, and voice cloning with PlayHT."
---

# PlayHT Connector for Muse

A Muse agent skill that works with PlayHT's text-to-speech API: generate speech from text, browse the voice library, and clone a voice from a sample. Generation is metered in credits — the skill confirms before every TTS and every clone, naming the text or voice. Honest note: voice cloning is confirmation-gated and only appropriate where you have the rights to the voice; the SKILL.md ships with a default voice configured. Auth is an unusual combo — an Authorization header with your user id plus an `X-User-Id` header with your API key — so save both exactly. Output audio URLs are temporary — download immediately. Draft: written from PlayHT's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-playht
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-playht
- Category: Creativity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/playht

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

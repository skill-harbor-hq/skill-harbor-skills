<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: christos-antono-npctalk-voice-input
description: "Let the player talk to NPCs out loud: an always-on open mic detects speech against the room's noise..."
---

# voice-input

Let the player talk to NPCs out loud: an always-on open mic detects speech against the room's noise floor (an utterance starts 12 dB above the floor for 150 ms and ends after 700 ms of silence), push-to-talk and typing are fallbacks, the mic pauses while an NPC talks so its own voice is not transcribed, coughs, clicks and one-word fillers are dropped, fal's Nemotron ASR transcribes in about 0.4 s with the WAV sent inline, and what was heard is routed to the NPC within 5 m or looked at within 12 m.

- Listing: https://theskillharbor.com/products/christos-antono-npctalk-voice-input
- Fiche en français: https://theskillharbor.com/fr/products/christos-antono-npctalk-voice-input
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/christos-antono/NPCTalk

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

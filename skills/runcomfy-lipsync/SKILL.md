<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: runcomfy-lipsync
description: "Lip-sync faces to an audio track on RunComfy — Sync Labs, OmniHuman, Kling, Creatify"
---

# RunComfy Lipsync

💳 Paid API required — Curated by Skill Harbor — an intent router for lip-sync on RunComfy: it classifies the input shape (source video + audio, portrait still + audio, or script-only) and picks the right endpoint — Sync Labs sync v2 Pro or standard for mouth-swap on existing footage (premium mouth fidelity for hero dubs, cheaper tier for batch jobs), OmniHuman for avatar-style talking heads from a single portrait, Kling lipsync audio-to-video or text-to-video when the script generates the speech in-pass, Creatify for its own ecosystem, plus Wan 2-7 and HappyHorse options for scene control and social clips. By @genmedia-labs, listed here with credit to its creator. Requires the `runcomfy` CLI and a RunComfy account with paid generation credits — every generation is billed. Honest caveats: lip-sync is dual-use — the skill carries an explicit consent section and instructs the agent to refuse requests targeting real public figures without consent, but it does not gate inputs itself; confirm the speaker in the audio has consented to having their voice paired with the target face, since both rights must be in hand. Audio quality drives mouth quality — clean voiceover without a music bed syncs best. The skill runs shell commands (declared as `Bash(runcomfy *)`), so review what it runs. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/runcomfy-lipsync
- Fiche en français: https://theskillharbor.com/fr/products/runcomfy-lipsync
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/genmedia-labs/skills/blob/main/lipsync/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

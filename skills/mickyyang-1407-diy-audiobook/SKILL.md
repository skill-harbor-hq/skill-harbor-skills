<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mickyyang-1407-diy-audiobook
description: "Turn public-domain books into multi-voice audiobooks."
---

# DIY Audiobook for Muse

DIY Audiobook turns a book into a finished audiobook, voice by voice. Give Muse a public-domain text from Project Gutenberg, or your own writing, and it splits the text into quotes, casts a voice per character, synthesizes each clip, checks the quality, then mixes and packages the result. The default voices are free (edge-tts): no account, no key, no payment. Paid backends (MiniMax, OpenAI) exist for other voices, if you bring your own key.

Sandbox test, 2026-11-08: install passed, `check.py` passed on a test episode, and `synth.py` produced 5 real MP3 clips with the free voices (5/5). The full mix, video and cover steps were not tested, and neither were the paid backends.

Caveats:
- On Windows, run with `PYTHONUTF8=1` (or a UTF-8 terminal), or `doctor.py` and `selftest.py` fail on encoding.
- ffmpeg **and** ffprobe are required (`winget install ffmpeg` provides both). The music step fails without ffprobe.
- The repo is very young (created 2026-10-29, one push at vetting time). The sandbox test is the safety net, and it passed.

- Listing: https://theskillharbor.com/products/mickyyang-1407-diy-audiobook
- Fiche en français: https://theskillharbor.com/fr/products/mickyyang-1407-diy-audiobook
- Category: Audio
- Price: Free
- Verification: verified
- Source repo: https://github.com/mickyyang-1407/diy-audiobook

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

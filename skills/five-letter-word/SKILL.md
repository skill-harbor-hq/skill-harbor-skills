<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: five-letter-word
description: "A solo word guessing game in chat: one common five-letter word sealed before your first guess, 6..."
---

# Five-Letter Word

A Skill Harbor house build: a solo word guessing game refereed by your own Muse, right in chat. Your assistant picks one common five-letter word in the language of your conversation, French or English, from a curated everyday vocabulary, and seals it in a game state file before your first guess. You get 6 valid guesses to find it. There is no starting category, no hint to buy, and no help beyond the feedback itself: every guess has to earn its information. Games are unlimited, and a new one can start whenever you want.

The feedback is exact, and its hardest case is settled in writing: duplicate letters. Each valid guess is answered with one fixed grid: your five letters, then five squares, green for a letter in the right place, yellow for a letter present elsewhere, grey for an absent letter, then the colour counts and your guess counter. The squares are computed in two passes, greens first, each one consuming its occurrence of the target word, then yellows from left to right only while an unconsumed occurrence remains. A letter is therefore never credited more times in one guess than it actually appears in the word, and a grey square on a repeated letter means fully counted, never a false claim that the letter is absent.

The frame stays firm in the ways that keep the game honest. A guess that is not a real word of the game's language, has the wrong length, contains non-letters, or repeats an earlier guess is rejected in one sentence, consumes nothing, and returns no...

- Listing: https://theskillharbor.com/products/five-letter-word
- Fiche en français: https://theskillharbor.com/fr/products/five-letter-word
- Category: Games
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/house-skills/blob/main/five-letter-word/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

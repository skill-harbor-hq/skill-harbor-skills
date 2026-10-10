<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hangman-plus
description: "Solo hangman in chat with a sealed word: 7 lives, a wrong word costs 2, and two bounded Plus..."
---

# Hangman Plus

A Skill Harbor house build: a game of hangman for one player, refereed by your own Muse, right in chat. Your assistant draws a word from an announced category, animals, jobs, geography, food, nature, objects, sports and leisure, sciences, and more, then seals the word, its category and its definition in a game state file before the first letter is proposed. You only ever see the mask, the category, your lives and the letters already tried. The sealed word never changes mid-game and is never revealed before the end, so the refereeing stays honest from the first letter to the last.

The rules are plain and fixed. You have 7 lives: a letter that is not in the word costs 1 life, and a wrong guess at the whole word costs 2, while a correct letter reveals all of its positions at once. The word is always 5 to 9 letters, drawn from curated French and English lists and checked at the draw: a common word, in normalized form, with no proper names except in the dedicated category the player chooses on purpose. A proposal you already made is never counted twice, an invalid entry costs nothing and does not use up your turn, and guessing the whole word exactly wins at once, even on the first turn.

The Plus is two bounded aids, each usable once per game. The definition token reveals the dictionary definition written into the state at the draw, one short sentence that never contains the word itself, for 15 points off a victory. The rescue letter token reveals one letter that is in the word...

- Listing: https://theskillharbor.com/products/hangman-plus
- Fiche en français: https://theskillharbor.com/fr/products/hangman-plus
- Category: Games
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/house-skills/blob/main/hangman-plus/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

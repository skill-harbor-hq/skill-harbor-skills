<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: word-chain
description: "A cooperative group word game refereed by your assistant in your own group chat: chain words of one..."
---

# Word Chain

A Skill Harbor house build: Word Chain, the cooperative word game, refereed by your own Muse inside a group chat you own. In the public thread, 2 to 8 registered players chain words of one imposed category for the round: each word must start with the last letter of the previous word, and no word may be repeated. The group plays together against the chain stopping, not against each other, and it is asynchronous on purpose: there is no imposed turn order, the chain advances whenever a player passes through the thread, until the lives run out or the announced inactivity deadline is reached.

The referee referees by reading the thread. This game has no hidden information at all: players propose their word directly in the group thread, no private message is needed for a proposal to count, and every verdict is public. After each proposal the referee checks, in a fixed order, the attack letter (purely mechanical, accents and case normalized), non-repetition against the chain recorded in the state file, then membership in the category, judged with the referee's own lexicon. A genuinely debatable category word is accepted on the benefit of the doubt, and the referee says why. Each validated fault, letter, repetition or a clear category miss, costs the group exactly 1 of its 3 collective lives; at 0, the round ends. When the expected letter is impossible or near-impossible in the category, the group may spend 1 life on its one letter joker per round and change just the expected...

- Listing: https://theskillharbor.com/products/word-chain
- Fiche en français: https://theskillharbor.com/fr/products/word-chain
- Category: Games
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/house-skills/blob/main/word-chain/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

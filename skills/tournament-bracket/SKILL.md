<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: tournament-bracket
description: "A single-elimination tournament refereed by your assistant inside your own group chat: every duel..."
---

# Tournament Bracket

A Skill Harbor house build: a single-elimination tournament, refereed by your own Muse inside a group chat you own. From 4 to 16 players sign up in the thread, and the bracket does the rest: quarter-finals or semi-finals depending on the count, one round per period you choose, and a final that crowns a champion. If the headcount is not a power of two, the bracket rounds up and the missing places become byes, given to the earliest signups in timestamped order, no draw, no favour, while signup order itself makes the seeds, crossed in the classic way so the top seed meets the lowest.

Every duel is a mini-quiz, and it is never a shared one. Each opponent receives their own questions in a private 1:1 message, different questions for the two players, always, balanced for comparable difficulty and passed through a full quality gate, and answers privately before the round's shared deadline. The fairness is structural: before the first question of a duel is sent, the referee writes both question sets, their complete answer keys, and one sealed reserve question per player into the state file. Nobody can be favoured after the fact, because the key predates the play; once the duel closes, its key is published with the result and anyone can recount. The score is simply the number of correct answers.

Ties are settled by a written rule, announced before anyone plays, never by chance: first a sudden-death question for each player, sealed the same way; if that still does not separate them...

- Listing: https://theskillharbor.com/products/tournament-bracket
- Fiche en français: https://theskillharbor.com/fr/products/tournament-bracket
- Category: Games
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/house-skills/blob/main/tournament-bracket/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

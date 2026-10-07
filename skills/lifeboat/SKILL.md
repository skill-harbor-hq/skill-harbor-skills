<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: lifeboat
description: "Give your AI a memory that survives the session, and a backup that protects it all."
---

# Lifeboat

AI assistants forget everything when the chat ends, and their files can vanish with one wrong click. Lifeboat is a build you install once: your AI maintains its own memory in plain files, backs them up on a schedule, and runs a guard that makes sure nothing slips through the cracks.

How it works:

1. Paste the keeper guide into your AI's instructions.
2. It sets up a small set of files: a curated memory (durable facts, preferences, decisions), an operating manual (how you two work together, lessons learned), and dated journals (what was done, when, with what result).
3. After each session, it files away what matters: a preference you stated, a decision you made, a lesson from something that went wrong. Transcripts and routine chatter stay out; only the durable stuff goes in. And at any time you can say "forget X": it removes that fact from the memory files and confirms. Your memory obeys you, not the other way around.
4. Next time you talk, it reads the files first. No more repeating yourself, no more re-learning the same lessons.
5. It sets up a regular backup of all these files: a local copy plus a private repo, with rotation. A deleted file is never a lost file.
6. It installs a coverage guard: on a schedule, it checks that every important folder is actually in the backup, and reports anything new that isn't covered yet. Started a new project folder? It gets flagged before it's ever at risk. This guard exists because new folders have a habit of silently falling outside...

- Listing: https://theskillharbor.com/products/lifeboat
- Fiche en français: https://theskillharbor.com/fr/products/lifeboat
- Category: Productivity
- Price: Free
- Verification: verified
- Source repo: https://github.com/skill-harbor-hq/lifeboat

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

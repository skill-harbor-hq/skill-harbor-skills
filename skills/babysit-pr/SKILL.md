<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: babysit-pr
description: "Monitor a pull request through review and CI, quietly."
---

# babysit-pr

Many repos have AI review bots. They are helpful, even if they are not always right. Babysit PR starts from that fact: never write your own watcher, polling loop or sleep loop. Use one watcher per PR. In T3 Code, watch_pull_request wakes the agent when a check fails, the required checks pass, someone comments or reviews, or the branch conflicts. Everywhere else, pr-wait, from this skill's directory, prints one line per real event and exits 0 when the until condition is met or the PR merges, 1 when it needs the user, and 2 on bad input. Its ready mode means required checks green, Greptile or Macroscope reviewed the head, and no unresolved threads. Its green mode means required checks only, and any-change exits on the first event.

Only the thread that owns the PR watches it. A delegated child task never calls watch_pull_request, since the parent owns the PR. A wake is news, not a merge decision: the merge gate must be checked separately. When handing off, unwatch first, since a watched thread stays in Working and out of the user's inbox. A merge or close ends the watch on its own. When an event needs no action, the turn ends without a message, and "still waiting" is never posted.

Reviews follow strict rules: only act on checks and comments newer than the latest push, verify every bot finding against the source before changing code, fix real findings and CI failures, distinguish repository failures from infrastructure flakes, and reply with a written reason when dismissing...

- Listing: https://theskillharbor.com/products/babysit-pr
- Fiche en français: https://theskillharbor.com/fr/products/babysit-pr
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/t3dotgg/tstack

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

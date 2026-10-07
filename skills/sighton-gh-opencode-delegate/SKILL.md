<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: sighton-gh-opencode-delegate
description: "Claude Code plugin: delegate implementation to opencode's free models in a git worktree; Claude..."
---

# opencode-delegate

Curated by Skill Harbor: opencode-delegate is a Claude Code plugin (and plugin marketplace) that runs opencode-driven development. Claude brainstorms with you, writes an implementation plan with bite-sized tasks, and you approve it exactly once. Then, for each task, Claude writes a brief and dispatches an opencode session on a free model (Muse Spark 1.3 by default) inside a git worktree: the model implements, commits per step and runs the verification command. Claude re-runs verification itself, sends the diff to an opencode reviewer, loops on fixes, and finishes with a whole-branch review before offering to merge, open a PR or leave the branch alone. The skill's own posture: opencode models are capable engineers, and your leverage is the brief. By @Sighton-GH (Bryan Ma), listed here with credit to its creator. Honest caveats: your code is sent to opencode's models to be implemented, so keep secrets and sensitive code out of the briefs; tasks touching auth, secrets, crypto or payments trigger one extra confirmation; between plan approval and the end, only four things stop the run (a destructive operation, a security-sensitive action, a side effect outside the worktree, or a broken plan). Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/sighton-gh-opencode-delegate
- Fiche en français: https://theskillharbor.com/fr/products/sighton-gh-opencode-delegate
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Sighton-GH/opencode-delegate

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

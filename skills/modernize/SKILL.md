<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: modernize
description: "Bring an old pull request up to date, or say why it should close."
---

# modernize

Modernize starts with guardrails: pull the latest origin for the working branch, the main branch and any related branch before starting; treat existing worktree changes as user-owned, using a disposable worktree when the active worktree is dirty or in use elsewhere; and remember that modernizing authorizes rebasing and updating the PR branch only. It does not authorize merging, closing, changing the base branch, or expanding scope. It never uses an unqualified force push: a rebased branch is updated with force-with-lease against the head SHA observed before the rebase. It posts no PR comment unless the user asked for one.

The PR's intent is established first: URL, state, base, head repository and branch, current head SHA, author, checks and review state, plus title, body, linked issues, commits, review threads and complete diff. The smallest coherent goal the PR was trying to accomplish is stated before its implementation is judged. Then the base branch is inspected for commits and diffs added since the PR diverged, including merged and open PRs that suggest a replacement or a competing implementation. The check looks beyond overlapping lines: has the same user-facing problem already been solved, did APIs, types, schemas, dependencies or architectural boundaries change, do both sides now claim the same behavior, was the code deleted, moved or intentionally simplified, would landing the PR restore an old behavior or create two ways to do the same thing, and is the original...

- Listing: https://theskillharbor.com/products/modernize
- Fiche en français: https://theskillharbor.com/fr/products/modernize
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

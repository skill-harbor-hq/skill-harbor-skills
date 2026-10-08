<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-terminal-ops
description: "Evidence-first repo execution: run commands, debug CI, make narrow fixes, and report exactly what..."
---

# Terminal Ops

Curated by Skill Harbor: an operator workflow for evidence-first terminal execution inside ECC harnesses. Use it when the user wants a command run, a repo checked, a CI failure debugged, or a narrow fix pushed with exact proof of what was executed and verified. Deliberately narrower than general coding guidance: resolve the working surface (exact repo path, branch, local diff state, requested mode), read the failing surface before changing anything, keep the fix narrow (one dominant failure at a time, smallest useful proving command first), and report execution state with exact status words: inspected, changed locally, verified locally, committed, pushed, or blocked. Pulls in companion skills when relevant: verification-loop for proving steps, tdd-workflow for regression coverage, security-review for secrets or auth, github-ops for CI and PR state, knowledge-ops for durable context. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: an operator workflow, not a sandbox; commands run for real. Never claim fixed until the proving command was rerun, never claim pushed unless the branch actually moved upstream, and never use destructive git commands. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-terminal-ops
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-terminal-ops
- Category: Claude Code
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/terminal-ops/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

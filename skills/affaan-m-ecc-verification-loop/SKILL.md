<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-verification-loop
description: "A six-phase verification gauntlet for any Claude Code session: build, type check, lint, tests with..."
---

# Verification Loop

Curated by Skill Harbor: a language-agnostic verification loop that makes Muse prove the work instead of vibing it. Six phases in order, stopping at the first hard failure. Build first: npm run build, with pipefail so piped output does not mask the exit code. Type check: tsc --noEmit for TypeScript, pyright for Python. Lint: the project's own lint script, ruff for Python. Tests with coverage: test suite run with coverage reporting, 80 percent minimum target, total, passed, failed, and coverage all reported. Security: greps for hardcoded secrets (sk- prefixes, api_key), console.log leftovers, and other low-hanging issues. Diff review: git diff stat and per-file review for unintended changes, missing error handling, and edge cases. The output is a fixed VERIFICATION REPORT template with PASS/FAIL per phase and an overall READY or NOT READY for PR verdict with issues to fix. A continuous mode is documented for long sessions: re-run the fast loop every 15 minutes or after major changes. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: secret greps are heuristics, not a substitute for real secret scanning; the gate is only as strict as the project's own tooling. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-verification-loop
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-verification-loop
- Category: Claude Code
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/verification-loop/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

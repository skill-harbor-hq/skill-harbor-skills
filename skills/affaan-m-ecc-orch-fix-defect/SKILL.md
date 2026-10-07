<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-orch-fix-defect
description: "Bug-fix orchestration that reproduces the defect as a failing regression test, delegates each phase..."
---

# Orchestrate bug fixes — reproduce as a failing test, fix to green, gated commit

Curated by Skill Harbor — @affaan-m's bug-fix orchestration discipline for agents: treat every fix as a pipeline, not a patch. First move is always reproducing the defect as a new failing regression test — proving the bug exists is what separates a fix from a tweak — then fix to green, run a code review, and commit behind an explicit pre-commit gate. The workflow delegates each phase to the matching ECC agent (code-explorer when the root cause is unclear, build-error-resolver for build breaks, security-reviewer on security-sensitive paths), skips the research phase by default (a light root-cause analysis only when the cause is non-obvious), and distinguishes clearly between fixing broken behavior, changing wanted behavior, and adding missing capability. MIT-licensed. Honest caveats: it is a thin wrapper over the `orch-pipeline` engine — the engine skill and the sibling ECC agents must also be installed; like any red-green workflow it works best where the codebase already has a runnable test suite. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-orch-fix-defect
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-orch-fix-defect
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/skills/orch-fix-defect/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

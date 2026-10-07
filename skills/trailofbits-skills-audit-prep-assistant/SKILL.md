<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: trailofbits-skills-audit-prep-assistant
description: "Get a codebase review-ready before an external security audit — review goals, static analysis..."
---

# Security audit preparation assistant

Curated by Skill Harbor — Trail of Bits' own audit-prep checklist, aimed at the 1–2 weeks before an external security review: set review goals (security objectives, areas of concern, worst-case scenarios, questions for the auditors), resolve easy issues first (run the right static analyzers per platform — slither for Solidity, dylint for Rust, golangci-lint for Go, CodeQL/Semgrep — triage every finding, raise test coverage toward untested code paths, remove dead code and unused libraries), make the code accessible (file list with scope, build instructions verified on a fresh environment, frozen commit/branch/tag, boilerplate vs original code identified), and generate the documentation auditors actually need (flowcharts and sequence diagrams, user stories, on-chain/off-chain assumptions, actors and privilege maps, function invariants and NatSpec, a glossary, optional video walkthroughs). It explicitly attacks the common rationalizations for skipping prep ("coverage looks decent", "I'll freeze later", "architecture is straightforward"), and ships an example audit-prep package as the target output. Honest caveats: **defensive use only — preparing your own code for review; it is not a substitute for the actual audit**; strongest on Solidity/Rust/Go stacks; CC-BY-SA-4.0 licensed (share-alike). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/trailofbits-skills-audit-prep-assistant
- Fiche en français: https://theskillharbor.com/fr/products/trailofbits-skills-audit-prep-assistant
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/trailofbits/skills/blob/main/plugins/building-secure-contracts/skills/audit-prep-assistant/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

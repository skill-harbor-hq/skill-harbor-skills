<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: fission-ai-openspec-verify-openspec-docs
description: "Fact-check finished OpenSpec documentation with a fresh-context subagent — re-run commands..."
---

# Verify OpenSpec docs: fresh-context fact-checking of documentation

Curated by Skill Harbor — @fission-ai's skill for verifying finished OpenSpec user documentation: a manually triggered verification pass (not part of the drafting loop — drafting belongs to write-openspec-docs, which is not bundled here). The method: scope the run to a page, one `##` section, or a list of changed claims; spawn one general-purpose subagent per unit with every placeholder filled and every path absolute. The reviewer plays two readers at once — a skeptical developer reading it cold and a fact-checker with the repo open — and checks, in order: Facts (re-run every terminal command shown — read-only commands anywhere, mutating ones only in a scratch directory; verify AI-surface commands like /opsx:propose against the skill sources; every output block must match actual output), Examples (any example spec must pass `openspec validate`), Structure (no re-explaining topics owned by other pages), Job fit (does the unit serve the page's one-line job?), Trust and slop (hype adjectives, claims without evidence, binary contrasts, colon reveals, em dashes, three punchy sentences in a row). Default is report, not rewrite: findings ranked most severe first, each with the quoted line and a one-line fix, plus exactly what was verified and how, and every claim that couldn't be verified and why. Fixes apply only on approval; two passes without converging means stop and escalate to the user. Honest caveats: designed for the OpenSpec repo's docs tree (the tree README's invariants...

- Listing: https://theskillharbor.com/products/fission-ai-openspec-verify-openspec-docs
- Fiche en français: https://theskillharbor.com/fr/products/fission-ai-openspec-verify-openspec-docs
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/fission-ai/openspec/blob/main/.agents/skills/verify-openspec-docs/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-inherit-legacy-style
description: "Stop AI style drift on legacy codebases: scan implicit conventions across 4 dimensions, resolve..."
---

# Inherit Legacy Style

Curated by Skill Harbor: a workflow skill that stops AI-generated code from drifting away from a hand-written legacy codebase's style. It auto-detects its mode: on a first run it measures the project scale (small, medium or large), scans the codebase across four meta-architecture dimensions (file anatomy, state and control flow, infrastructure placement, error handling), applies signal-threshold noise reduction so weak conflicts auto-resolve without bothering you, then grills you on strong conflicts strictly one question at a time, each with evidence and four options. The consensus becomes a .ai-style-rules.md with Golden Files (real exemplar paths), concrete naming and state-control rules, and DONTs, plus an optional enforcement hook (soft via CLAUDE.md reference, hard via PreToolUse, or none, your call). On later runs it does an incremental sniff: it diffs recent Git changes against the recorded rules, grills new conflicts the same way, and appends evolution logs without overwriting old rules. When hooked, every code-writing task opens with a compliance declaration naming the exemplar followed and the DONTs avoided. A community contribution to the ECC collection. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: it needs read/write access to your project root and your answers for the grilling step, so it is interactive by design; it aligns meta-architecture only, not syntax or stack quality, and it never copies...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-inherit-legacy-style
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-inherit-legacy-style
- Category: Legacy Code
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/inherit-legacy-style/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-rules-distill
description: "Turn repeated skill wisdom into rules for Muse: scans installed skills, extracts cross-cutting..."
---

# Rules Distill

Curated by Skill Harbor: a rules maintenance workflow that promotes recurring skill wisdom into rule files, so Muse stops relearning the same lessons every session. Applies the "deterministic collection plus LLM judgment" principle: scripts inventory skills and rules exhaustively, then the LLM cross-reads the full context and produces verdicts. Three phases: inventory (scan-skills.sh and scan-rules.sh collect every skill file and rule heading), cross-read and verdict (skills grouped into thematic clusters, each analyzed with the full rules text; candidates merged across batches with deduplication), and user review and execution (a report table with principle, verdict, target and confidence; you approve, modify or skip each candidate by number; results saved to results.json). A candidate only qualifies with 2+ skills of evidence, an actionable behavior change ("do X" / "don't do Y"), a clear violation risk, and no existing coverage in the rules. Verdicts: Append, Revise, New Section, New File, Already Covered, Too Specific. Design principles: what not how (principles only, code examples stay in skills), link back to source skills, deterministic collection with LLM judgment, and an anti-abstraction safeguard (the 2+ skills, actionable behavior, violation risk filter). Use for periodic rules maintenance, after installing new skills, or when rules feel incomplete relative to the skills in use. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-rules-distill
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-rules-distill
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/rules-distill/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

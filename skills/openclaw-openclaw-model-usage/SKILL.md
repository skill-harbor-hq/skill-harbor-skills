<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: openclaw-openclaw-model-usage
description: "Summarize CodexBar local cost logs by model for Codex or Claude — current-model or full per-model..."
---

# Model usage costs per model from CodexBar local logs (short listing)

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @openclaw's skill for summarizing CodexBar local cost logs by model, for Codex or Claude. The agent fetches cost JSON from the CodexBar CLI (`codexbar cost --format json --provider <codex|claude>`, or a file/stdin via `--input`) and runs the bundled `scripts/model_usage.py` summarizer: "current model" mode (most recent daily row, picks the highest-cost model) or "all models" mode, text or JSON output. Covers the current-model logic, inputs (Homebrew formula installer for live local reads on macOS/Linux, AUR package or release tarballs on Linux), outputs (cost-only per model — tokens are not split by model in CodexBar output), and a CLI reference. Honest caveats: requires the third-party CodexBar CLI installed (not part of OpenClaw) — live reads only on macOS/Linux, other platforms go through exported JSON; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/openclaw-openclaw-model-usage
- Fiche en français: https://theskillharbor.com/fr/products/openclaw-openclaw-model-usage
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/openclaw/openclaw/blob/main/skills/model-usage/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

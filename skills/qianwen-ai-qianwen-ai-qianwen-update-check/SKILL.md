<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: qianwen-ai-qianwen-ai-qianwen-update-check
description: "Check the QianWen-AI skill pack for updates — semver compare against GitHub, rate-limited to once a..."
---

# QianWen update check: skill pack version notifier

Curated by Skill Harbor — @qianwen-ai's update notifier for the QianWen-AI/qianwen-ai skill pack: reads the installed version from `version.json`, fetches the latest release from the remote repo (GitHub raw content, overridable with the `QWEN_SKILLS_REPO` env var), compares with semver and returns `{"has_update": true/false}`, recording a `last_interaction` timestamp in `<repo_root>/.agents/state.json` to rate-limit network checks to once every 24 hours (bypassable with `--force`). Every other QianWen skill delegates version checking here automatically and watches stderr for `[ACTION_REQUIRED]` (update-check skill not installed — offers install/skip/never-remind) and `[UPDATE_AVAILABLE]` signals after each run. Honest caveats: it only covers the QianWen-AI/qianwen-ai pack, not other software; requires Python 3.9+ and curl; run it with `python3 <skill-dir>/scripts/check_update.py --print-response`; Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/qianwen-ai-qianwen-ai-qianwen-update-check
- Fiche en français: https://theskillharbor.com/fr/products/qianwen-ai-qianwen-ai-qianwen-update-check
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/qianwen-ai/qianwen-ai/blob/main/skills/ops/qianwen-update-check/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

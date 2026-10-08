<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-terminal-opener
description: "Open any executable in a visible host terminal via a shell-free launch plan: dry-run by default..."
---

# Terminal Opener

Curated by Skill Harbor: a reusable, shell-free launch plan for opening an executable and its argument array in a visible terminal window, built for agent harnesses that need to start an interactive CLI, an SSH session, a local development process, a sandbox or any argv-based command on the host. The launcher preserves the executable and every argument as separate process entries, never interpolates a shell command string, and keeps every spawn on shell: false. It defaults to a non-launching plan and opens a real window with --launch only after the user explicitly requests it and the argv has been reviewed. WezTerm mux is tried first with a detached wezterm start fallback when the mux is unavailable, and --recover or --standalone modes start a detached process that skips user configuration. JSON output supports capability detection, dry-run inspection and diagnosing mux failures. From the affaan-m/ECC repository (MIT). Honest caveats: the launched process inherits the full environment of the calling process, including secret-bearing variables, so run it from a shell whose environment is safe to expose; terminal support is limited to what the script detects. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-terminal-opener
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-terminal-opener
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/terminal-opener/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

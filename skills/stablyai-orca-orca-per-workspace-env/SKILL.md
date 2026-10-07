<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: stablyai-orca-orca-per-workspace-env
description: "Resolve the right Orca executable and load the version-matched guide for per-workspace environment..."
---

# Orca per-workspace environments: recipe setup and doctor

Curated by Skill Harbor — @stablyai's Orca environment-recipe helper: resolve the correct Orca executable once per session (ORCA_CLI_COMMAND if set, `orca-dev` in a dev checkout, `orca-ide` on Linux outside Orca-managed terminals — never bare `orca`, which normally resolves to the GNOME Orca screen reader and starts speech on the user's machine), then load the version-matched guide with `ORCA skills get orca-per-workspace-env` before running any command, so per-workspace environment recipes — the on-demand, disposable runtimes (cloud sandbox, VM, SSH host, or local container) Orca creates fresh for each workspace — are stood up end to end, fixed in `environmentRecipes` entries in `orca.yaml`, scaffolded with provider lifecycle scripts, or debugged via `orca vm recipe doctor`. Includes handling for `runtime_access_denied` sandbox errors (re-run with escalated permissions, do not restart Orca) and unknown `skills get` (update Orca; use --help for read-only discovery, never guess unsupported commands). Honest caveats: this is a discovery stub — the real guidance ships inside the installed Orca executable, and it does not work without Orca installed; listed here with credit to its creator; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/stablyai-orca-orca-per-workspace-env
- Fiche en français: https://theskillharbor.com/fr/products/stablyai-orca-orca-per-workspace-env
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/stablyai/orca/blob/main/skills/orca-per-workspace-env/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

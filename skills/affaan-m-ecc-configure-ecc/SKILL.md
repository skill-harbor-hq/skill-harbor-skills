<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-configure-ecc
description: "Conversational setup wizard for ECC itself: inventory, scope and hook-mode choices, dry-run..."
---

# Configure ECC

Curated by Skill Harbor: the conversational setup wizard for ECC itself. Runs inside the current harness: inventory the install without changing anything, collect exactly two choices (scope: user, project, or local; hook mode: off, minimal, standard, or strict), preview with a dry-run, ask one yes/no confirmation, apply non-interactively, verify the result, and render the welcome only after success. Routes by harness: full scope-and-hook wizard in Claude Code, Codex's native plugin lifecycle in Codex, project-surface install under ./.kimi-code in Kimi. Never clones ECC into a temporary directory or copies plugin components by hand, and never runs a bare interactive setup through a non-TTY harness shell. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this is a meta skill about ECC itself; it is only useful inside an ECC harness (Claude Code, Codex, or Kimi). It is a post-install reconfiguration path and cannot intercept or replace a provider's built-in first-install UI. After verified changes, run /reload-plugins or restart the harness. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-configure-ecc
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-configure-ecc
- Category: Claude Code
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/configure-ecc/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

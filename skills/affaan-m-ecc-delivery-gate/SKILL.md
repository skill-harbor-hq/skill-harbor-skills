<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-delivery-gate
description: "A mechanical Stop hook for Claude Code: blocks session finish until quality checks pass, using..."
---

# Delivery Gate

Curated by Skill Harbor: a mechanical quality gate for Claude Code, implemented as a Stop hook that runs only deterministic checks, no AI inference. Before Claude may finish a session it verifies three machine-readable facts: rationalization patterns in the transcript tail (regex heuristics like "skip tests for now", warning only, never blocking alone because heuristics can false-positive), stale learning libraries (filesystem mtime on configurable paths, blocking when three or more are stale or the growth log is stale on a complex task), and disk space (warning under 50 GB, hard block under 15 GB). It complements reasoning gates like self-audit the way CI pipeline gates complement code review: one checks facts, the other checks judgment. The failure mode it targets is real: sessions that ship working code while session hygiene was neglected, learning never captured, shortcuts rationalized, disk silently filling. Installation is one file copy plus a settings.json entry. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: regex warnings can false-positive (that is why they only warn); the hook enforces habits, it cannot make the captured learning good. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-delivery-gate
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-delivery-gate
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/delivery-gate/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

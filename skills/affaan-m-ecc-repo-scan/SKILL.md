<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-repo-scan
description: "A pinned-commit installer for the repo-scan skill: clone first, review the pinned commit, then..."
---

# Repo Scan (bootstrap pointer)

Curated by Skill Harbor: a bootstrap pointer that installs the external repo-scan skill from a pinned, reviewable commit. This ECC pointer does not perform the audit itself; it exists so repo-scan is installed before you run its cross-stack source-code asset audit. The real tool looks across C++, Android, iOS, and Web to answer: how much code is actually yours, what is third-party, and what is dead weight. Use it when taking over a large legacy codebase and needing a structural overview, before major refactoring, when auditing third-party dependencies embedded directly in source instead of declared in package managers, or when preparing architecture decision records for a monorepo reorganization. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this is a pointer, not the audit; installation clones external code, so review the pinned commit before installing; the audit maps structure, it does not judge quality. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-repo-scan
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-repo-scan
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/repo-scan/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-opensource-pipeline
description: "Safely open-source a private project: a 3-stage pipeline (fork, sanitize, package) that strips..."
---

# Open-Source Pipeline

Curated by Skill Harbor: a 3-stage pipeline that takes a private project public without leaking secrets. Stage one forks the project into a staging directory and strips credentials, tokens, and private config; stage two runs the sanitizer to verify nothing sensitive survived; stage three packages the result with a generated CLAUDE.md, a setup.sh, and a README so strangers can actually use it. Commands cover the full run (/opensource fork), verify-only, package-only, plus list and status for staged projects. The protocol asks the questions that matter before touching anything: which license (MIT, Apache-2.0, GPL-3.0, BSD-3-Clause), which GitHub org or user, which repo name, and proposes a README description from analyzing the project. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: automated sanitizing catches the obvious, not the clever; always review the staged copy yourself before pushing public, and choose your license deliberately because you cannot take it back. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-opensource-pipeline
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-opensource-pipeline
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/opensource-pipeline/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

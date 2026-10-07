<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-security-review
description: "Security checklist for Muse: secrets management, input validation, auth patterns, and API..."
---

# Security Review

Curated by Skill Harbor: a security review skill that turns Muse into a systematic code auditor for the moments that matter most: adding authentication, handling user input, working with secrets, creating API endpoints, or touching payment and sensitive features. Instead of vague advice it ships a concrete, checkable list: secrets management (no hardcoded keys, env vars verified at startup, .env.local in .gitignore, nothing sensitive in git history, production secrets in the hosting platform), input validation with schemas (zod examples for emails, ranges, and required fields), plus patterns for authentication, authorization, API hardening, and third-party integrations. Every rule comes with FAIL/PASS code pairs so the difference between vulnerable and safe is unmistakable, and verification steps you can tick off before merging. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a checklist, not a penetration test; it catches common mistakes, not novel attack chains; always review security-related code yourself, and never paste real secrets into any chat. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-security-review
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-security-review
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/security-review/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

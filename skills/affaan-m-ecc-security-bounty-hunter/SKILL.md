<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-security-bounty-hunter
description: "Hunt remotely reachable, bounty-worthy vulnerabilities in repos: SSRF, auth bypass, injection..."
---

# Security Bounty Hunter

Curated by Skill Harbor: a practical vulnerability-hunting playbook tuned for one question: does this actually pay? The skill biases hard toward remotely reachable, user-controlled attack paths and throws away the patterns bounty platforms routinely reject as informative or out of scope. In scope: SSRF through user-controlled URLs, auth bypass in middleware or API guards, remote deserialization and upload-to-RCE paths, SQL injection in reachable endpoints, command injection in request handlers, path traversal in file-serving paths, auto-triggered XSS. Explicitly skipped unless the program says otherwise: local-only pickle.loads, eval in CLI-only tooling, hardcoded shell=True, missing security headers alone, generic rate-limit complaints, self-XSS, out-of-scope CI injection, demo or test-only code. The workflow: check program scope first (rules, SECURITY.md, disclosure channel, exclusions), find real entrypoints (HTTP handlers, uploads, background jobs, webhooks, parsers, integration endpoints), use static tooling as triage input only, read the real code path, then prove exploitability before writing the report. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: only hunt on targets you are authorized to test; a checklist is not a pentest and never submit unverified findings. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-security-bounty-hunter
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-security-bounty-hunter
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/security-bounty-hunter/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

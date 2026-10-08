<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-django-security
description: "Harden Django with Muse: production settings, auth and RBAC, ORM injection prevention, XSS and..."
---

# Django Security Best Practices

Curated by Skill Harbor: a security hardening guide that makes Muse review a Django application the way a security-minded reviewer would. It starts with the production settings that matter (DEBUG off, allowed hosts from the environment, secure cookies, HSTS, required secret key), then covers authentication with a custom user model, Argon2 password hashing and session configuration, and authorization with model permissions, DRF permission classes and role-based access control. SQL injection prevention leans on the ORM with parameterized raw() examples and the dangerous f-string interpolation marked as vulnerable. XSS prevention covers template auto-escaping, the safe filter rules, and escapejs for JavaScript contexts. CSRF protection covers secure cookie flags, trusted origins and AJAX token handling. File uploads get magic-bytes MIME validation cross-checked against extensions plus size limits, API security gets throttling and JWT/token authentication, and the skill closes with security headers, CSP middleware, secret management and a quick deployment checklist. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a checklist is not a pentest, run a real security review for anything handling sensitive data; never paste real secrets into a chat while using it. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-django-security
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-django-security
- Category: Django
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/django-security/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

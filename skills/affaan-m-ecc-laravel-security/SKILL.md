<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-laravel-security
description: "Harden Laravel with Muse: production config, Sanctum and Passport auth, Gates and Policies..."
---

# Laravel Security Best Practices

Curated by Skill Harbor: a security hardening guide that makes Muse review a Laravel application against the framework's real security surface. It starts with production configuration (APP_DEBUG off, APP_KEY set and validated at boot, secure session cookies, HTTPS enforcement with correctly scoped trusted proxies), then covers authentication with Sanctum token abilities, Argon2/bcrypt password hashing, strong password rules with breach checking, and session regeneration on login. Authorization covers Gates with a super-admin before() hook, model Policies wired through controllers and Blade, and role middleware. Eloquent security is a highlight: fillable whitelisting instead of open guarded arrays, safe() and validated() over request all(), parameterized whereRaw, and hidden attributes for API responses. CSRF covers the VerifyCsrfToken middleware with careful webhook-only exemptions, XSS covers Blade auto-escaping and the dangerous raw echo with user input, input validation covers FormRequest rules with post-validation sanitization, and API security covers per-endpoint rate limiters, Sanctum versus Passport guidance, and CORS whitelisting. File uploads get MIME, size and dimension validation with private-disk storage and signed URLs, and the skill closes with composer audit in CI, secret management, encrypted queue payloads and a security event audit log. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a checklist...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-laravel-security
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-laravel-security
- Category: Laravel
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/laravel-security/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

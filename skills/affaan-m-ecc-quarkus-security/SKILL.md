<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-quarkus-security
description: "Hardened Quarkus for Muse: JWT and OIDC auth, @RolesAllowed RBAC, Bean Validation, parameterized..."
---

# Quarkus Security

Curated by Skill Harbor: security implementation patterns for Quarkus applications, so Muse wires authentication and authorization the safe way. Covers JWT authentication (MicroProfile JWT, SmallRye) and OIDC configuration with secrets from environment variables, custom authentication filters, role-based access control with @RolesAllowed and programmatic SecurityIdentity checks including ownership verification, input validation with Bean Validation annotations and custom validators, SQL injection prevention via parameterized Panache queries and parameterized native queries (never string concatenation), BCrypt password hashing with a dedicated service, CORS configuration with explicit origins and methods, secrets management via environment variables or HashiCorp Vault (never in application.properties), rate limiting with the X-Forwarded-For spoofing warning (use the container remote address or an authenticated identity, configure trusted proxies), security headers (X-Frame-Options, HSTS, CSP without unsafe-inline scripts), audit logging of sensitive operations, and dependency CVE scanning with OWASP dependency-check. Includes BAD/GOOD code pairs throughout. Use when adding authentication or authorization, validating input, managing secrets, or hardening a Quarkus application. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: security guidance, not a penetration test; rate limiting and CORS must be adapted to your...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-quarkus-security
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-quarkus-security
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/quarkus-security/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

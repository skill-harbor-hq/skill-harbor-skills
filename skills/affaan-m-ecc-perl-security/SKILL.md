<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-perl-security
description: "Secure Perl for Muse: taint mode, allowlist validation, safe process execution, DBI placeholders..."
---

# Perl Security

Curated by Skill Harbor: comprehensive Perl security guidelines that turn Muse into a careful reviewer of Perl code touching user input, the shell, or the network. Starts where Perl security starts: taint mode (-T), tracking external data and forcing explicit validation before unsafe use, with the untainting regex pattern done right (and the lazy /(.*)/ called out as pointless). Then outward: allowlist-over-blocklist input validation with length constraints, ReDoS prevention (no nested quantifiers, possessive quantifiers, timeouts on untrusted patterns), safe file operations (three-argument open, lexical filehandles, TOCTOU and path traversal defenses), safe process execution (list-form system and exec, IPC::Run3, never string-form shell interpolation), SQL injection prevention (DBI placeholders everywhere, allowlisted dynamic columns, DBIx::Class safety), and web security (HTML::Entities output encoding per context, CSRF tokens, secure session config, security headers). Ships a perlcritic security configuration and a quick checklist table for reviews. Every rule comes with GOOD/BAD pairs, including the critical ones: two-arg open on user data, string-form system calls, interpolated SQL. Use when reviewing Perl input handling, process execution, DBI queries, or web-facing code (CGI, Mojolicious, Dancer2, Catalyst). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a checklist, not a penetration test; Perl's...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-perl-security
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-perl-security
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/perl-security/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

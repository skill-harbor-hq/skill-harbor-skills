<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-springboot-verification
description: "Verify a Spring Boot service before every PR with Muse: build, static analysis, tests with JaCoCo..."
---

# Spring Boot Verification Loop

Curated by Skill Harbor: a pre-PR verification loop for Spring Boot that makes Muse produce a pass or fail readiness report instead of vibes. Six phases, Maven and Gradle variants. Build runs with parallel threads, stopping on the first failure. Static analysis chains SpotBugs, PMD, and Checkstyle. Tests are concrete: Mockito unit tests for service logic including a duplicate-email exception case, Testcontainers integration tests against real Postgres wired with DynamicPropertySource instead of H2, and MockMvc API tests checking 201 and 400 responses, with JaCoCo reporting lines and branches covered. Security scanning runs OWASP dependency-check for CVEs plus greps for secrets in source and yml, System.out.println, raw exception messages in responses, and wildcard CORS origins. An optional Spotless phase handles formatting, and the diff review checklist catches leftover debug logs, weak HTTP statuses, missing transactions, and undocumented config changes. The output is a structured VERIFICATION REPORT template with Build, Static, Tests, Security, Diff lines and an overall READY or NOT READY verdict with issues to fix. A continuous mode is documented for long sessions: re-run the fast loop of mvn test plus SpotBugs every 30 to 60 minutes. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: the secret greps are heuristics, real secret management needs dedicated tooling; the gate is only as strict as you keep it. Skill...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-springboot-verification
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-springboot-verification
- Category: Spring Boot
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/springboot-verification/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-quarkus-verification
description: "Run the full Quarkus pre-PR gauntlet with Muse: build, static analysis, tests with JaCoCo coverage..."
---

# Quarkus Verification Loop

Curated by Skill Harbor: a full verification loop for Quarkus services that makes Muse run the same gauntlet before every PR, after major refactors, and pre-deploy. Ten phases, from build to docs. Build uses mvn clean verify or the Gradle equivalent, stopping on the first compilation error. Static analysis chains Checkstyle, PMD, and SpotBugs, with an optional SonarQube pass, flagging unused imports, high cyclomatic complexity, and null-pointer risks. Tests come in three flavors, all spelled out: Mockito unit tests (with the Panache persist-is-void trap documented), Testcontainers integration tests with real Postgres, and REST Assured API tests for 201 and 400 cases, with JaCoCo enforcing 80 percent line and 70 percent branch coverage. Security scanning covers OWASP dependency-check CVEs, quarkus:audit for vulnerable extensions, ZAP API scans against the OpenAPI surface, plus a checklist of secrets in env vars, input validation, auth, CORS, security headers, BCrypt, parameterized queries, and rate limiting. Native compilation tests the GraalVM build with container-build, with troubleshooting for reflection, resources, and JNI. Then k6 load testing, health check probes on /q/health, container image build with Trivy and Grype scans, config validation per environment, and a docs review including OpenAPI regeneration. A single automated bash script chains the phases and a CI-ready GitHub Actions workflow is included. By @affaan-m, listed here with credit to its creator. From the...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-quarkus-verification
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-quarkus-verification
- Category: Quarkus
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/quarkus-verification/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

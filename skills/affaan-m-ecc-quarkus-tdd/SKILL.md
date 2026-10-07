<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-quarkus-tdd
description: "Test-driven development for Quarkus 3.x: JUnit 5, Mockito, @Nested organization, Camel route..."
---

# Quarkus TDD

Curated by Skill Harbor: a test-driven development workflow for Quarkus 3.x services that keeps Muse writing tests first and coverage high. The loop is explicit: write failing tests, implement the minimum to pass, refactor while green, enforce 80%+ line coverage (70%+ branch) with JaCoCo. Unit tests follow a strict shape: @Nested classes grouped by method under test, @DisplayName for readable reports, given/when/then naming, AAA comments, AssertJ assertions, and Mockito verify() including never() for error paths. Goes deep on event-driven testing: Apache Camel routes tested with AdviceWith and MockEndpoint (replacing RabbitMQ endpoints with mocks, weaving assertions into routes), event services with success and error event verification, CompletableFuture async operations including LogContext propagation, and REST Assured resource tests for the HTTP layer. Integration tests use @QuarkusTest with real databases via test profiles, and the Maven setup (dependencies, JaCoCo prepare-agent/report/check) is spelled out copy-ready. Use when adding features, fixing bugs, or refactoring Quarkus services, especially event-driven ones. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: aimed at Quarkus 3.x LTS, adjust for other versions; Camel route testing has real learning curve, the examples help but expect setup friction; 80% coverage is a floor for discipline, not a guarantee of correctness. Skill Harbor never reviews the...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-quarkus-tdd
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-quarkus-tdd
- Category: Testing
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/quarkus-tdd/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

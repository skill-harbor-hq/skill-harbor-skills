<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-java-coding-standards
description: "Write and review Java 17+ with Muse: Spring Boot and Quarkus conventions, naming, records and..."
---

# Java Coding Standards

Curated by Skill Harbor: a Java coding-standards guide that makes Muse write and review Java 17+ the way each framework expects. It starts by detecting your framework from the build file (quarkus, spring-boot, or shared Java conventions only) and applies the right conventions automatically. Naming covers PascalCase classes and records, camelCase methods and fields, UPPER_SNAKE_CASE constants, plus the framework split: *Resource for Quarkus JAX-RS endpoints, *Controller for Spring. Immutability favors records and final fields, with the deliberate Quarkus exception for Panache active-record entities where public fields are idiomatic. Optional usage covers find* methods returning Optional with map and flatMap instead of get(). Streams get the rule for short pipelines, loops for clarity when it gets complex. Dependency injection prefers constructor injection in both frameworks, flags Spring field injection with @Autowired as a fail, and warns against @Singleton where @ApplicationScoped is needed in Quarkus. Reactive patterns cover Uni and Multi pipelines, failWith on null, and the blocking-call-inside-Uni trap. Exceptions get domain-specific unchecked exceptions with centralized handlers (RestControllerAdvice in Spring, ExceptionMapper or @ServerExceptionMapper in Quarkus). Generics, per-framework project layout, logging (SLF4J versus JBoss), configuration (@ConfigurationProperties versus @ConfigMapping), and testing expectations (@WebMvcTest and @DataJpaTest slices in Spring...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-java-coding-standards
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-java-coding-standards
- Category: Java
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/java-coding-standards/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

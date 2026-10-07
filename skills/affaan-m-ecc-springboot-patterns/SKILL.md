<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-springboot-patterns
description: "Production Spring Boot for Muse: REST layer, controller-service-repository structure, JPA, caching..."
---

# Spring Boot Patterns

Curated by Skill Harbor: Spring Boot architecture patterns for building scalable, production-grade Java services with Muse. Covers the full vertical slice: REST controllers (thin, validated, paginated, returning ResponseEntity with proper status codes), the controller to service to repository layering, Spring Data JPA repositories with @Query methods, @Transactional service methods, DTOs as records with Bean Validation annotations, centralized exception handling via @ControllerAdvice (validation errors, access denied, generic fallback), caching with @Cacheable/@CacheEvict, @Async processing, structured SLF4J logging, request logging filters, pagination and sorting with PageRequest, retry with exponential backoff for external calls, rate limiting with Bucket4j (including the X-Forwarded-For spoofing warning and trusted proxy setup), background jobs, and observability (Micrometer, tracing). Production defaults included: constructor injection over field injection, RFC 7807 problem details, HikariCP tuning, read-only transactions for queries. Use when building or reviewing a Spring Boot backend, structuring the REST layer, or adding caching, validation, or async work. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: patterns assume Spring Boot 3+; rate limiting and security notes need adapting to your deployment topology (proxies, containers); the skill guides structure, you still own the domain logic. Skill Harbor...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-springboot-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-springboot-patterns
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/springboot-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-hexagonal-architecture
description: "Ports & Adapters guidance for Muse: keep domain logic independent from frameworks and I/O, with..."
---

# Hexagonal Architecture

Curated by Skill Harbor: a Ports & Adapters (hexagonal architecture) skill that helps Muse design, implement, and refactor systems where business logic stays independent from frameworks, transport, and persistence. It teaches the full vocabulary: a framework-free domain model, use cases as pure orchestration, inbound ports describing what the application can do, outbound ports describing what it needs (repositories, gateways, clock, UUID), adapters implementing those ports at the edges (HTTP controllers, DB repositories, queue consumers), and a single composition root where everything is wired. Dependencies always point inward, so you can swap a database, an external API, or a message bus without rewriting business rules. Works across TypeScript, Java, Kotlin, and Go, for new features where maintainability matters and for refactoring layered code where domain logic got tangled with I/O. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: ports and adapters add indirection, overkill for throwaway scripts; the skill guides the design, you still write the code. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-hexagonal-architecture
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-hexagonal-architecture
- Category: Architecture
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/hexagonal-architecture/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

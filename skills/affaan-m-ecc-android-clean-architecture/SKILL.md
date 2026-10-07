<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-android-clean-architecture
description: "Clean Architecture for Android and Kotlin Multiplatform: module layout, strict dependency rules..."
---

# Android Clean Architecture

Curated by Skill Harbor: an architecture skill for structuring Android and Kotlin Multiplatform projects so they stay testable as they grow. It prescribes a module layout (app, core, domain, data, presentation, design-system, plus optional feature modules) with strict dependency rules: domain is pure Kotlin and must never depend on data, presentation, or any framework. You get the UseCase and Repository patterns with repository interfaces living in domain and implementations in data, data layer design with Room, SQLDelight, and Ktor, data flow guidance between layers, and dependency injection setup with Koin or Hilt. The domain-never-depends-on-data rule is the load-bearing wall: it keeps business logic unit-testable without Android on the classpath. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; a multi-module setup has real upfront cost, so tiny apps may find it heavy; the KMP notes assume Kotlin fluency. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-android-clean-architecture
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-android-clean-architecture
- Category: Android
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/android-clean-architecture/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

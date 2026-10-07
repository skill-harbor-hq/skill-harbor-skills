<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-cpp-coding-standards
description: "Modern C++ (17/20/23) for Muse, from the C++ Core Guidelines: RAII, const-correctness, smart..."
---

# C++ Coding Standards

Curated by Skill Harbor: C++ coding standards derived from the C++ Core Guidelines (isocpp.github.io) that make Muse write modern, safe, idiomatic C++17/20/23. Organized by guideline area with rule numbers you can cite: philosophy and interfaces (express intent, statically type-safe, no resource leaks, immutability by default), functions (single logical operation, constexpr and noexcept where fitting, return values over output parameters, F.16 parameter passing), classes (Rule of Zero or Rule of Five, explicit single-argument constructors, virtual destructors), resource management (RAII everywhere, raw pointer means non-owning, unique_ptr over shared_ptr, make_shared, never naked new/delete), expressions (always initialize, {} syntax, const by default, nullptr not NULL, no C-style casts), error handling (throw by value, catch by reference, custom exception types, destructors never fail), const-correctness (Con.1 to Con.5), concurrency (scoped_lock, never call unknown code under a lock, no volatile for synchronization), templates with C++20 concepts, standard library preferences (vector by default, string_view to observe, '\n' not endl), enumerations (enum class, no ALL_CAPS), source file and naming conventions (include guards, no using namespace in headers, underscore_style), and performance (don't optimize without measurements). Every section ships DO/DON'T pairs plus a quick-reference completion checklist. Use when writing, reviewing, or refactoring C++ code, making...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-cpp-coding-standards
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-cpp-coding-standards
- Category: C++
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/cpp-coding-standards/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

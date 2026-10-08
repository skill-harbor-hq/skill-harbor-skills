<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-dotnet-patterns
description: "Write and review idiomatic C# with Muse: records and immutability, async/await with cancellation..."
---

# .NET Development Patterns

Curated by Skill Harbor: an idiomatic .NET pattern guide that makes Muse write and review C# the way experienced .NET developers do. Core principles first: prefer immutability with sealed records and init-only properties, be explicit about nullability and access modifiers, and depend on abstractions with interface-based services registered in the DI container. Async guidance is strict: async all the way with CancellationToken threaded through, Task.WhenAll for independent parallel operations, and never .Result or .Wait on the happy path because of deadlock risk. The Options pattern binds config sections to strongly-typed objects via IOptions, the Result pattern returns explicit success or failure records instead of throwing for expected failures, and the EF Core repository pattern shows Include plus AsNoTracking for read paths. It also covers a request-timing middleware example, organized minimal APIs with MapGroup, RequireAuthorization, and TypedResults, guard clauses that keep the happy path un-nested with ArgumentNullException.ThrowIfNull and range checks, and a sharp anti-pattern table: async void, empty catch blocks, new Service in constructors, public fields, dynamic in business logic, mutable static state, and string.Format in loops, each with its fix. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: modern C# idioms assumed (records, required members), adapt if you maintain older frameworks; guidance, not a...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-dotnet-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-dotnet-patterns
- Category: .NET
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/dotnet-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

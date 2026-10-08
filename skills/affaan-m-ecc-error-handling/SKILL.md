<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-error-handling
description: "Robust error handling patterns for TypeScript, Python and Go: typed errors, retries, circuit..."
---

# Error Handling Patterns

Curated by Skill Harbor: consistent, robust error handling patterns for production applications in TypeScript, Python and Go. Five core principles anchor everything: fail fast and loudly (surface errors at the boundary where they occur, never bury them); typed errors over string messages (errors are first-class values with structure, e.g. an AppError hierarchy with code and statusCode in TypeScript); user messages are not developer messages (friendly text for users, full context logged server-side); never swallow errors silently (every catch block must handle, re-throw or log); and errors are part of your API contract (document every error code a client may receive). Covers designing error types and exception hierarchies, retry logic with backoff and circuit breakers for unreliable dependencies, reviewing API endpoints for missing handling, user-facing failure messages, and debugging cascading failures or silent error swallowing. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: these are patterns to adapt to your stack, not a linter; some teams will disagree on details (exceptions vs result types), pick one convention and hold it. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-error-handling
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-error-handling
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/error-handling/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-fastapi-patterns
description: "Production-grade FastAPI: project layout, Pydantic v2, dependency injection, auth, and pytest with..."
---

# FastAPI Patterns

Curated by Skill Harbor: modern, production-grade FastAPI development patterns. Covers the full slice: project layout with an app factory and lifespan management, settings via pydantic-settings, shared dependencies, SQLAlchemy engine and session handling, routers split by domain, separate Pydantic request/response schemas versus ORM models, and a transactional service layer for business logic. Then the cross-cutting concerns: dependency injection done right, async handlers, authentication and authorization, CORS and middleware, and testing with httpx and pytest (including the conftest patterns that make API tests fast and isolated). The guide is explicit about where beginners cut corners, like creating tables on startup for demos versus managing schemas with Alembic migrations in strict production. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: Python and FastAPI only; the async SQLAlchemy patterns assume a modern stack (Pydantic v2, SQLAlchemy 2.x), older codebases will need adaptation. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-fastapi-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-fastapi-patterns
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/fastapi-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

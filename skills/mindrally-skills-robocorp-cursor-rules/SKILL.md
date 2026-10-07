<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mindrally-skills-robocorp-cursor-rules
description: "Receive-an-object-return-an-object tasks, Pydantic over raw dicts, async I/O for database calls..."
---

# RoboCorp RPA Python guidelines: functional tasks, Pydantic validation, async-first automation

Curated by Skill Harbor — @mindrally's RoboCorp development guidelines: a functional, declarative style for RPA robots — plain functions with `def`/`async def`, full type hints, Pydantic `BaseModel` validation over raw dictionaries, the Receive-an-Object-Return-an-Object (RORO) pattern, descriptive `is_`/`has_` boolean names, guard clauses with the happy path last, structured files (exported tasks → sub-tasks → utilities → types), middleware for logging and error monitoring, async everything I/O-bound, caching for static data, and specific exception handling (`RPA.HTTP.HTTPException`). Includes RPA-specific performance priorities (execution time, resource utilization, throughput) and conventions like RoboCorp's dependency injection. Honest caveats: guidance only — it assumes a RoboCorp/Python RPA setup and will not turn a general agent into an RPA expert without one; RoboCorp-specific bits (dependency injection, RPA libraries) only apply in that ecosystem. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mindrally-skills-robocorp-cursor-rules
- Fiche en français: https://theskillharbor.com/fr/products/mindrally-skills-robocorp-cursor-rules
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mindrally/skills/blob/main/robocorp-cursor-rules/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

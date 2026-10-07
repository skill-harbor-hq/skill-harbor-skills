<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: martinholovsky-claude-skills-generator-async-programming
description: "Concurrent Python (asyncio) and Rust (Tokio) done safely: race-condition prevention, locks and..."
---

# Async Programming — race-free asyncio and Tokio with a TDD workflow

Curated by Skill Harbor — @martinholovsky's async-programming: an async programming skill for Python (asyncio) and Rust (Tokio) with TDD-first discipline. Core principles: write async tests before implementation, performance awareness (asyncio.gather, semaphores, no blocking calls), identify race conditions at await points, protect shared state with locks/atomic ops, manage resources with async context managers, handle errors in concurrent contexts, avoid deadlocks. Ships a decision framework, concrete bad-vs-good code patterns (gather, semaphores, TaskGroups, executors for CPU work), atomic DB operations, graceful shutdown with cancellation handling, a security standards section (race conditions, TOCTOU, CVE-2024-12254 and others), common anti-patterns, and phased checklists. Honest caveats: the skill self-declares risk_level MEDIUM — race conditions and timing vulnerabilities are the subject matter, and the content is defensive (how to prevent them), not offensive; it points to bundled references/ files (security examples, advanced patterns) that ship with the repo. The skill's frontmatter states no license; the catalog manifest records Unlicense — manifest takes precedence. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/martinholovsky-claude-skills-generator-async-programming
- Fiche en français: https://theskillharbor.com/fr/products/martinholovsky-claude-skills-generator-async-programming
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/martinholovsky/claude-skills-generator/blob/main/skills/async-programming/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

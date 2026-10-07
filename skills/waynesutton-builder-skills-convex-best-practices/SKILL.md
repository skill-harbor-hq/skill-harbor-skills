<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: waynesutton-builder-skills-convex-best-practices
description: "Validators, indexed reads, idempotent mutations, OCC conflict avoidance, pagination, and the..."
---

# Convex best practices: production patterns and the ESLint plugin rules

Curated by Skill Harbor — @waynesutton's Convex production playbook: the patterns that keep a Convex app fast and correct in production. The rules that matter most: validators on every function (args and returns, with returns: v.null() when nothing comes back); indexes, not filters — every table read goes through withIndex; idempotent mutations that return early when the doc is already in the target state; patch without reading first; Promise.all for independent writes; schedule internal.* only; thin wrappers with business logic in plain helpers that take ctx; ConvexError for anything a client should read. Plus a deep dive on optimistic concurrency control (where write conflicts come from — shared docs, wide reads, fast repeat calls — and how idempotent design avoids them), event records instead of counters (or the sharded-counter/aggregate component at scale), dedup windows for heartbeats, pagination over .collect(), no Date.now() in queries, and the @convex-dev/eslint-plugin (install command and config) to catch old patterns at lint time. Includes a worked example (tasks table with by_user_and_status index) and a common-mistakes table. Honest caveats: Convex-specific — only useful if you build on Convex (account + project required for real use); patterns only, the agent still needs a Convex project to apply them. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/waynesutton-builder-skills-convex-best-practices
- Fiche en français: https://theskillharbor.com/fr/products/waynesutton-builder-skills-convex-best-practices
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/waynesutton/builder-skills/blob/main/skills/convex-best-practices/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

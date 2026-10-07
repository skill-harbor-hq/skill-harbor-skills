<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: dboeckli-ai-agent-skills-skill-best-practices
description: "Create, structure and improve Claude skills — description-as-trigger design, kebab-case naming..."
---

# Build reliable Claude skills: SKILL.md structure, triggers, validation

Curated by Skill Harbor — @dboeckli's guide for creating, structuring, and improving Claude skills: a 7-step workflow. Step 1, identify your use-case category — Document & Asset Creation, Workflow Automation, or MCP Enhancement — and define 2–3 concrete use cases first. Step 2, create the kebab-case folder with exactly `SKILL.md` inside. Step 3, write the description — the most critical part — with WHAT it does AND WHEN to use it (specific trigger phrases users actually say, under 1024 chars, no XML tags). Step 4, write body instructions following the template: `## Instructions` → numbered steps → `## Examples` → `## Troubleshooting`, specific and actionable, details in `references/`, keep SKILL.md under 5,000 words. Step 5, update the skill tables in CLAUDE.md and README.md. Step 6, run the bundled `validate-skills.sh` (fix every FAIL; check frontmatter scalars, indentation, forbidden characters). Step 7, test triggering with 10–20 queries (target ~90% on relevant queries, never on unrelated ones) and iterate on the signals — undertriggering → add trigger phrases; overtriggering → add negative triggers; instructions ignored → move critical steps to the top. Includes the full design principles (progressive disclosure, composability, portability), five workflow patterns, a troubleshooting table (won't upload, under/over-triggering, instructions ignored, context bloat), and a quick checklist. Honest caveats: methodology only — a couple of steps are specific to the author's...

- Listing: https://theskillharbor.com/products/dboeckli-ai-agent-skills-skill-best-practices
- Fiche en français: https://theskillharbor.com/fr/products/dboeckli-ai-agent-skills-skill-best-practices
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/dboeckli/ai-agent-skills/blob/master/.claude/skills/skill-best-practices/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: cypress-io-ai-toolkit-cypress-docs
description: "Answer Cypress questions from official docs only — llms.txt-first lookup with an anti-hallucination..."
---

# Cypress docs lookup for agents

Curated by Skill Harbor — @cypress-io's official docs-search skill for agents: whenever a task depends on finding, reading or quoting Cypress documentation — commands, APIs, assertions, lifecycle hooks, config options, env vars, CLI flags, plugins, TypeScript types — the agent searches docs.cypress.io first using the LLM-optimized docs strategy (fetch `/llms.txt`, prefer the markdown endpoints under `/llm/*`, fall back to standard pages, then changelog and blog), classifies the query type (how-do vs what-is vs API vs config vs CI/CD vs errors), routes errors to the error-message reference, and extracts structured content (syntax, required vs optional arguments, return behavior, version awareness). Its hard rule is anti-hallucination: never assume a feature is missing, never invent APIs or syntax, and when a claim cannot be verified, say "I could not verify this in Cypress docs" with the closest supported alternative instead of guessing. Honest caveats: documentation lookup only — it does not write or fix tests (the skill points to sibling skills `cypress-author` and `cypress-explain` for those, which are not bundled here); needs live access to docs.cypress.io at run time; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/cypress-io-ai-toolkit-cypress-docs
- Fiche en français: https://theskillharbor.com/fr/products/cypress-io-ai-toolkit-cypress-docs
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/cypress-io/ai-toolkit/blob/main/skills/cypress-docs/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

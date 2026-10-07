<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: github-awesome-copilot-eval-driven-dev
description: "Instrument your Python LLM app with pixie-qa — define eval criteria, build golden datasets, run..."
---

# Eval-driven development: build a real eval pipeline for Python LLM apps

Curated by Skill Harbor — @github's eval-driven development skill for Python LLM applications, powered by the pixie-qa package: a 6-step agent workflow. Step 1, analyze the app and define eval criteria derived from real failure modes (not generic quality dimensions). Step 2, instrument the app with `wrap()` calls at its data boundaries, write a Runnable that invokes the real entry point, and capture a reference trace. Step 3, turn criteria into runnable evaluators (the agent evaluator is the default for semantic criteria, custom functions only for mechanical checks). Step 4, build a golden dataset from real-world data — never the project's own test fixtures. Step 5, run `pixie test` until it completes with real scores. Step 6, analyze outcomes and write a prioritized action plan. Hard rules: the app's LLM calls must go to a REAL LLM — no mocking, no faking, or scores are meaningless; a web server (`pixie start`) runs alongside for live result viewing. Honest caveats: methodology plus tooling — the pixie-qa package and its web server are prerequisites (setup.sh in the skill); running evals makes real LLM API calls (real API costs); Python 3.10+. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/github-awesome-copilot-eval-driven-dev
- Fiche en français: https://theskillharbor.com/fr/products/github-awesome-copilot-eval-driven-dev
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/github/awesome-copilot/blob/main/skills/eval-driven-dev/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: langfuse-skills-langfuse
description: "Docs-first agent workflows for Langfuse: instrumentation, datasets, experiments, evaluations..."
---

# Langfuse — official skill for LLM observability, evals and prompt management

Curated by Skill Harbor — the official @langfuse skill for agents working with Langfuse LLM observability. Its core principles: never implement from memory — always fetch current docs first (Langfuse ships fast), use the `langfuse-cli` for querying and modifying data, pin exact SDK versions in plans, and never guess at UI labels when guiding users through the interface. The skill routes each use case to a dedicated reference: instrumenting applications, building evaluation datasets, migrating prompts from codebases, prompt engineering, setting up evals and LLM-as-a-Judge calibration, error analysis, user-feedback capture, CI/CD experiment gates, and v4 project migration — plus three ways to read the docs live (llms.txt index, per-page markdown fetch, doc/issue search API). It also defines a feedback path so users can report when the skill itself is wrong. MIT-licensed. Honest caveats: you need a Langfuse project and API keys (Langfuse Cloud offers a free tier — save keys in the vault, never paste them into chat; self-hosting is also possible); distinct from the community `bluman1-langfuse` connector already listed — that one is a lean MCP-style connector for browsing traces and scoring, this is the vendor's full engineering playbook; docs-first means real network calls to langfuse.com every run. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/langfuse-skills-langfuse
- Fiche en français: https://theskillharbor.com/fr/products/langfuse-skills-langfuse
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/langfuse/skills/blob/main/skills/langfuse/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

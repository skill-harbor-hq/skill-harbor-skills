<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: celigo-ai-configuring-ai-agents
description: "Build LLM-powered import steps and safety guardrails in Celigo flows — provider choice..."
---

# Configure Celigo AI agents and guardrails

💳 Paid Celigo account required — Celigo is a paid integration platform (iPaaS), and AI-agent usage counts against the account's monthly AI token quota. Curated by Skill Harbor — @celigo's skill for configuring AI agents and guardrails: an AI agent is an LLM-powered import step inside a Celigo flow (records flow in, the model classifies/extracts/validates/generates, structured output flows back into the pipeline); a guardrail renders a fixed verdict (`flagged: true|false` plus reasoning) that the parent flow routes on — PII detection/masking, content moderation, or custom AI validation. The skill covers provider choice (OpenAI via the Responses API, or Gemini via LiteLLM proxy), prompt design, structured output (`json_schema`/`text`/`blob`), tool use (web search, MCP, Celigo Tools, image generation), response mapping, conversation history via a stable identifier, the Celigo AI vs BYOK decision (platform-managed credentials with a curated model list and token quota vs your own API key), a capability check before building, CLI commands (`celigo ai-agents`, `celigo guardrails`), a pre-submit checklist, gotchas (PUT erases omitted fields, case-sensitive `adaptorType`, Gemini model IDs need the `gemini/` prefix), and a common-errors table. Honest caveats: useless without a Celigo platform account — the CLI, the schemas and the quotas all live there; BYOK moves costs to your own provider billing. MIT licensed. Skill Harbor never reviews the code, review it yourself before use....

- Listing: https://theskillharbor.com/products/celigo-ai-configuring-ai-agents
- Fiche en français: https://theskillharbor.com/fr/products/celigo-ai-configuring-ai-agents
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/celigo/ai/blob/main/skills/configuring-ai-agents/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

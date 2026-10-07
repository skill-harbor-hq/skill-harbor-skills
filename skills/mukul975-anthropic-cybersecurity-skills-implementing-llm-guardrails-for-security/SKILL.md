<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mukul975-anthropic-cybersecurity-skills-implementing-llm
description: "Harden LLM apps with input/output guardrails — NeMo Guardrails (Colang) flows, Python PII..."
---

# LLM guardrails for security — input/output validation with NeMo Guardrails, Presidio, and Guardrails AI

Curated by Skill Harbor — @mukul975's guardrails skill: a complete defensive playbook for adding input/output safety controls to LLM applications. The agent installs the guardrail frameworks (NeMo Guardrails for Colang-based rail flows, Guardrails AI for structured output validation, Microsoft Presidio and spaCy for PII detection), runs a guardrails pipeline agent in multiple modes (full, input-only, output-only, PII redaction, JSON for dashboards), authors JSON content policies (allowed/blocked topics, blocked patterns, PII categories), writes Colang 2.0 flow definitions (input rails like self-check, jailbreak check, sensitive-data masking; output rails like hallucination check), and deploys the whole thing as validation middleware around an LLM app or RAG pipeline. It ships key-concept explanations, a tools inventory, verification checks (injection patterns blocked, PII redacted, <200 ms input-only latency), and an honest scope boundary: guardrails are defense-in-depth, not a replacement for authentication, authorization, or network security. Honest caveats: needs Python 3.10+ and real installs (nemoguardrails, presidio, a spaCy model); the self-check rails call a model — an OpenAI API key (billed) or a local LLM endpoint, so costs are avoidable with a local model. Apache-2.0 licensed (frontmatter and manifest agree). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mukul975-anthropic-cybersecurity-skills-implementing-llm-guardrails-for-security
- Fiche en français: https://theskillharbor.com/fr/products/mukul975-anthropic-cybersecurity-skills-implementing-llm-guardrails-for-security
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mukul975/anthropic-cybersecurity-skills/blob/main/skills/implementing-llm-guardrails-for-security/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

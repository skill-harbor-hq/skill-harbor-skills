<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-agent-architecture-audit
description: "Diagnose a misbehaving agent across 12 stack layers, from system prompt to hidden repair loops..."
---

# Agent Architecture Audit

Curated by Skill Harbor: a full-stack diagnostic workflow for agent and LLM applications that hide failures behind wrapper layers. It audits 12 layers (system prompt, session history, long-term memory, distillation, active recall, tool selection, tool execution, tool interpretation, answer shaping, platform rendering, hidden repair loops, persistence) against five failure patterns: wrapper regression (the model is fine, the wrapper makes it worse), memory contamination (old topics leaking into new conversations), tool discipline failure ("must use tool X" only in prompt text, never enforced in code), rendering or transport corruption, and hidden agent layers silently mutating output. Four-phase workflow: scope the audit, collect evidence (with rg recipes for each anti-pattern), map failures (symptom, mechanism, source layer, root cause, evidence, confidence), then a code-first fix strategy ordered by severity (critical, high, medium, low) with a structured JSON report schema. Includes 7 quick diagnostic questions and a blunt reporting rule: if the system is broken, say so directly. It references sibling ECC skills (agent-introspection-debugging, agent-eval, security-review, autonomous-agent-harness, agent-harness-construction), which are separate skills not all listed here. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: built for developers with codebase access; inside Muse it works as a diagnostic interview and...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-agent-architecture-audit
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-agent-architecture-audit
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/agent-architecture-audit/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: qianwen-ai-qianwen-ai-qianwen-model-selector
description: "Pick the right Qwen model for the task — interactive diagnostics or fast-path lookup, with..."
---

# Qwen model selector and cost advisor

Curated by Skill Harbor — @qianwen-ai's advisor for choosing between Qwen models: it starts by detecting the API key type (Token Plan `sk-sp-` key, standard PAYG key, or nothing configured — without blocking when no key is set), then works in two modes — interactive advisory (a five-question diagnostic: content type, task, quality/speed/cost priority, input size, structured output) or fast-path cross-skill resolution for execution skills that need a model decision without user interaction. Model lists and recommendations are resolved from versioned CDN catalogs with local fallbacks, never fabricated; current pricing, availability and quotas come from the QianWen CLI (`qianwen models list/info/search`, `qianwen usage`), which is the authoritative source — snapshots are explicitly forbidden as proof of current state. The skill enforces two separate credential systems (API key for model calls vs browser device-flow login for the CLI, never confused), never outputs credentials in plaintext, and mandates a pricing disclaimer on every cost-related answer. Honest caveats: **Qwen API calls are billed pay-as-you-go or through a Token Plan — a free-tier command (`qianwen usage free-tier`) exists but free quota is never guaranteed, verify before use**; live data requires Node 18+ and the QianWen CLI installed. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/qianwen-ai-qianwen-ai-qianwen-model-selector
- Fiche en français: https://theskillharbor.com/fr/products/qianwen-ai-qianwen-ai-qianwen-model-selector
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/qianwen-ai/qianwen-ai/blob/main/skills/models/qianwen-model-selector/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: blockedpath-pi-meta-oauth
description: "Use Muse Spark models inside pi via OAuth device login; prompt-cache friendly, dynamic model..."
---

# pi-meta-oauth

Paid API required: this extension is free, but using it bills your Meta Model API account (standard models from $1.25/$4.25 per million input/output tokens; discounted contributor models cost cents per million but allow Meta to use your prompts and completions for product improvement, including training future models). Curated by Skill Harbor: pi-meta-oauth connects the pi coding agent to Meta's Model API through OAuth. Install it, run `/login meta`, and pi walks you through a device-code login against auth.meta.com that mints a Model API key (re-minted daily, stored in ~/.pi/agent/auth.json). It routes Muse Spark models through pi's openai-responses provider, where the prompt cache actually works (cache is near 0% on the chat-completions route), sends prompt_cache_retention 24h by default, and keeps a dynamic Muse model catalog with the real 1M-token context windows. By @BlockedPath (Justin Barlow), listed here with credit to its creator. Honest caveats: the opt-in META_MUSE_USER_AGENT=1 flag makes pi identify as Meta's first-party Muse client to unlock reasoning effort "max" on the contributor model; it relies on undocumented server behavior, is not supported by Meta, may stop working without notice and may conflict with Meta's terms, so enable it only if you accept that risk; use a standard model such as muse-spark-1.3 if you do not want the contributor terms. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/blockedpath-pi-meta-oauth
- Fiche en français: https://theskillharbor.com/fr/products/blockedpath-pi-meta-oauth
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/BlockedPath/pi-meta-oauth

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

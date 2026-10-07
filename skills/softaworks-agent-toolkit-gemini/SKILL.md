<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: softaworks-agent-toolkit-gemini
description: "Delegate code reviews, plan reviews, and >200k-token analyses to Gemini 3 Pro via the Gemini CLI —..."
---

# Gemini CLI for agents: code review and big-context analysis

Curated by Skill Harbor — @softaworks's skill for running the Gemini CLI from an agent: use when asked to activate Gemini for code review, plan review, or big-context (>200k tokens) processing. It carries a model table (gemini-3-pro-preview as the default flagship, gemini-3-flash for speed, 2.5 variants as legacy cost options) with a critical background-mode warning: never use --approval-mode default in non-interactive shells — it hangs forever on approval prompts; use yolo for automated runs or wrap with timeout, plus a troubleshooting guide for hung Gemini processes (detect via ps, kill, prevent). Covers command assembly (model, approval mode, -i interactive, --include-directories, --sandbox), common use cases (background code review, plan review, big-context analysis, interactive-only terminal review), follow-up session habits, and error handling (stop and report failures, ask permission before yolo on high-impact flags). Honest caveats: you need the Gemini CLI installed (v0.16.0+ for Gemini 3) and a Google API key — Gemini API usage is billed; note that yolo mode auto-approves ALL tool actions, so background reviews can execute anything the CLI can do — scope the prompt and directory tightly; and Gemini CLI sessions are one-shot, no resume — follow-ups start a new session. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/softaworks-agent-toolkit-gemini
- Fiche en français: https://theskillharbor.com/fr/products/softaworks-agent-toolkit-gemini
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/softaworks/agent-toolkit/blob/main/dist/plugins/gemini/skills/gemini/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mims-harvard-tooluniverse-tooluniverse-sdk
description: "Build and test tools with the ToolUniverse framework — local tool registration, test-case..."
---

# ToolUniverse SDK — build and test agent tools

Curated by Skill Harbor — @mims-harvard's ToolUniverse SDK skill: a TDD-style workflow for developing tools inside the open-source ToolUniverse framework (2 000+ agent tools across 40 domains). The agent's tasks: add/update local tool definitions with the `run`/`register_tool`/`register_remote_tool` APIs, generate test cases with `TestCaseGenerator` (from config docs or free-text requirements), validate with the interactive test loop (`iterate_and_validate`) — which spins up a ToolUniverse API server in `server_mode`, syncs the local tool, and iterates the LLM agent through failures until the tool passes — then release through the remote release flow with the ToolUniverse HTTP API (`/tools/register_remote_tool`, `/release`), requiring `TOOLUNIVERSE_API_KEY` for remote calls. Reference material covers the tool data model (definitions, arguments, results, error types), OpenAPI import, the HTTP API client, and the test-case generator config. Honest caveats: the core is open source (Apache-2.0) and local dev needs nothing but Python — an OpenAI key is only used by the LLM-search parts of the tool database, not by the SDK workflow itself; remote registration/release needs a ToolUniverse API key — save it in your secure vault, never paste a live key here. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mims-harvard-tooluniverse-tooluniverse-sdk
- Fiche en français: https://theskillharbor.com/fr/products/mims-harvard-tooluniverse-tooluniverse-sdk
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mims-harvard/tooluniverse/blob/main/plugin/skills/tooluniverse-sdk/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

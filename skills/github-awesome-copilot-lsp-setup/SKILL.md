<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: github-awesome-copilot-lsp-setup
description: "Enable code intelligence in GitHub Copilot CLI — detect the OS, install the right language-server..."
---

# LSP setup for GitHub Copilot CLI

Curated by Skill Harbor — @github's utility skill for installing and configuring Language Server Protocol servers for the GitHub Copilot CLI. A 7-step workflow: ask which language (via `ask_user` with choices), detect the OS, look up the server and install command in `references/lsp-servers.md`, ask the config scope (user-level `~/.copilot/lsp-config.json` or repo-level `lsp.json` / `.github/lsp.json`), install the server binary, write and merge the JSON config (never clobber existing entries), and verify the binary is on `$PATH` with valid JSON — unlocking go-to-definition, find-references, hover and type info. Documents the `lspServers` config schema (`command`, `args --stdio`, `fileExtensions` mapping), restart semantics (`/exit` then relaunch, check with `/lsp`). Honest caveats: utility only — needs the Copilot CLI installed and a package manager to fetch the server binary; unlisted languages require a manual web search for the right server. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/github-awesome-copilot-lsp-setup
- Fiche en français: https://theskillharbor.com/fr/products/github-awesome-copilot-lsp-setup
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/github/awesome-copilot/blob/main/skills/lsp-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

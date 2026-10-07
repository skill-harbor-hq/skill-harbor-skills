<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: nodnarbnitram-claude-code-extensions-tauri-v2
description: "Build cross-platform desktop/mobile apps — tauri.conf.json, Rust commands, IPC patterns..."
---

# Tauri v2+ development: Rust backend, IPC, permissions, mobile builds

Curated by Skill Harbor — @nodnarbnitram's Tauri v2+ development skill: build cross-platform desktop and mobile apps with a web frontend and Rust backend. Quick start: create Tauri commands (#[tauri::command]) and register them in generate_handler! (unregistered commands silently fail), call them from the frontend with @tauri-apps/api/core (the v1 @tauri-apps/api/tauri API is gone), and declare capabilities/permissions — Tauri v2 denies everything by default. Critical rules: owned types (never &str) in async commands, never block the main thread, all shared logic in lib.rs (main.rs stays a thin passthrough — required for mobile), capabilities added before any plugin feature is used. Includes the tauri.conf.json configuration reference (devUrl, CSP, bundling), a known-issues prevention table (command not found, permission denied, white screen, mobile build failures, sidecar/updater issues), IPC patterns (events, channels, state management with Mutex<T>, error handling across the serde boundary), plugin list with mandatory permission strings, mobile-vs-desktop behavioral differences, and a setup checklist. Honest caveats: code-first reference — the agent still needs the Tauri toolchain installed (npx tauri info, Rust targets, platform SDKs for mobile) and a real project; verified against official docs as of 2026-04-02 — check the Tauri changelog for newer changes. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/nodnarbnitram-claude-code-extensions-tauri-v2
- Fiche en français: https://theskillharbor.com/fr/products/nodnarbnitram-claude-code-extensions-tauri-v2
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/nodnarbnitram/claude-code-extensions/blob/main/.claude/skills/tauri-v2/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

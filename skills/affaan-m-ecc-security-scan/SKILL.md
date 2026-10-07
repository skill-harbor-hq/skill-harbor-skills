<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-security-scan
description: "Audit your Claude Code setup for Muse: scans .claude/ configs (CLAUDE.md, settings, MCP servers..."
---

# Security Scan

Curated by Skill Harbor: a security audit for your Claude Code configuration, so Muse helps you find the holes in the very setup it runs on. Uses AgentShield (github.com/affaan-m/agentshield, npm package ecc-agentshield). Scans the .claude/ directory file by file: CLAUDE.md for hardcoded secrets, auto-run instructions and prompt injection patterns ; settings.json for overly permissive allow lists, missing deny lists and dangerous bypass flags ; mcp.json for risky MCP servers, hardcoded env secrets and npx supply chain risks ; hooks/ for command injection via interpolation, data exfiltration and silent error suppression ; agents/*.md for unrestricted tool access and prompt injection surface. Produces a graded report (A secure to F critical) in terminal, JSON, Markdown or self-contained HTML, with severity-ranked findings and an auto-fix mode that replaces hardcoded secrets with env references and tightens wildcard permissions (manual-only suggestions are never touched). Includes an Opus deep-analysis mode running an attacker/defender/auditor three-agent pipeline, plus a GitHub Action for CI. Use when setting up a new Claude Code project, after modifying configs, before committing configuration changes, or for periodic security hygiene. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: AgentShield must be installed (npm install -g ecc-agentshield, or run via npx) ; the Opus deep analysis needs an ANTHROPIC_API_KEY...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-security-scan
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-security-scan
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/security-scan/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

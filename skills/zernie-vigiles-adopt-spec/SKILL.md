<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: zernie-vigiles-adopt-spec
description: "Start a typed CLAUDE.md.spec.ts from your existing hand-written instructions — faithful..."
---

# Adopt a typed spec for your hand-written CLAUDE.md

Curated by Skill Harbor — @zernie's adopt-spec skill for the vigiles tooling: adopt a typed .spec.ts for an existing hand-written CLAUDE.md (or AGENTS.md) — starting from the file you already have, non-destructively. The adoption rules are non-negotiable: faithful (preserve every rule, command, key file and prose section as-is — the spec must compile back to ~your existing file), non-destructive (never edit the original; only write the new .spec.ts; switching to spec-managed is a separate explicit step), don't escalate enforcement (keep guidance() as guidance() — upgrading to enforce() is the separate strengthen skill), reversible (vigiles eject hands the file back as plain markdown anytime), and ask before writing (present the generated spec and summary first; write only on yes). The workflow: read the existing file (and check vigiles is installed — suggest npm install -D vigiles if not), parse the structure (commands, key files, rules with **Enforced by:** or **Guidance only** annotations, prose), classify each rule (linter-backed → enforce("linter/rule"), code-review-backed → guidance(), unannotated → TODO), generate the spec file (claude({sections, keyFiles, commands, rules}) with file()/cmd()/ref() refs enabling stale-reference detection), verify it compiles (npx vigiles compile and compare against the original), present the result (conversion counts, compile/lint commands, ask to write the file), optionally set up CI (GitHub Actions steps or the zernie/vigiles@v1...

- Listing: https://theskillharbor.com/products/zernie-vigiles-adopt-spec
- Fiche en français: https://theskillharbor.com/fr/products/zernie-vigiles-adopt-spec
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/zernie/vigiles/blob/main/skills/adopt-spec/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

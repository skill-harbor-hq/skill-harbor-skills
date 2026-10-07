<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: samber-golang-safety
description: "Defensive Go coding: kill nil panics and silent bugs."
---

# Go Defensive Coding Skill for Muse

Teaches Muse defensive Go coding: nil-interface traps (a typed nil pointer is not == nil), nil map writes, append backing-array aliasing, silent int64→int32 truncation, float == comparison, defer inside loops, goroutine and resource lifecycle, defensive copies of slices and maps, and zero-value design — each rule shown as a dangerous/good code pair. Expects a Go project and optionally golangci-lint for the errcheck/forcetypeassert/nilerr/govet/staticcheck rules it cites. Discovered via skills.sh. Honest note: it is prevention, not debugging — it explicitly hands off concurrency design, exploitable vulnerabilities, and failing-program diagnosis to sibling skills in the same repo (golang-concurrency, golang-security, golang-troubleshooting) that are not included here, so some sections point outward. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/samber-golang-safety
- Fiche en français: https://theskillharbor.com/fr/products/samber-golang-safety
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/samber/cc-skills-golang/blob/main/skills/golang-safety/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-click-path-audit
description: "Behavioral UI audit for Muse: trace every button through its state changes to catch bugs where..."
---

# Click-Path Audit

Curated by Skill Harbor: a behavioral flow audit that finds the bugs static code reading misses. Traditional debugging checks whether the function exists, whether it crashes, whether types line up. It never checks whether the final UI state matches what the button label promised, whether function B silently undoes what function A just did, or whether shared state has side effects that cancel the intended action. The motivating example: a "New Email" button called setComposeMode(true) then selectThread(null); both worked individually, but selectThread had a side effect resetting composeMode to false, so the button did nothing, and 54 other bugs found by systematic debugging had missed it. The method: first map every state store action to what it sets and what it silently resets (the critical reference), then audit each touchpoint handler call by call in order, checking six patterns: sequential undo, async races, stale closures, missing state transitions (button says Save but nothing saves), conditional dead paths, and useEffect interference. Each finding gets a severity, the exact trace with the conflicting call marked, expected versus actual state, and a specific fix. Includes scope control guidance (full app, single page, or store-focused audits, with a recommended parallel agent split) and positions itself after systematic debugging and before verification. Use when systematic debugging found "no bugs" but users report broken buttons, after modifying any shared state...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-click-path-audit
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-click-path-audit
- Category: Debugging
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/click-path-audit/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

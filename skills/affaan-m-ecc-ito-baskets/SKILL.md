<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-ito-baskets
description: "Read-only research on Ito baskets and prediction markets: index, compare, brief, or plan, never..."
---

# Ito Baskets

Curated by Skill Harbor: a strictly read-only research skill for Ito basket and prediction-market data. It works in exactly one of four modes per request: index (browse the live basket catalog and produce a normalized index table with provenance), compare (deterministic gap analysis of a basket against your own research, notes, or watchlist: match, conflict, missing, stale), brief (source-grounded market intelligence on events, venues, underliers, liquidity, and news context with retrieval metadata), or worksheet (a non-executable planning worksheet of constraints, observable status, and open questions for a human to review). The boundaries are non-negotiable and stated up front: it never advises buying, selling, holding, or sizing; never places, cancels, or simulates any order; has no execution path and no confirmation can give it one. Anonymous public reads need no key; keyed developer reads use a scoped read-only API key sent as a bearer token to the exact Ito Markets origin, and it will mark keyed access blocked and continue with public data rather than fabricate parity. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: prediction markets involve real-money positions, so use this for research and planning only, never as trading advice; the bundled read-only client runs Node scripts, which assumes a machine where you can run them. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-ito-baskets
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-ito-baskets
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/ito-baskets/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

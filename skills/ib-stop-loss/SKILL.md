<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-stop-loss
description: "Downside stop-loss management for PMCC, naked LEAPS and stock positions in a real Interactive..."
---

# IB Stop-Loss Manager

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. This skill connects to a REAL Interactive Brokers account and, in execute mode, it can place, modify and cancel real protective orders on that account: a wrong stop percentage, a wrong basis or a misread position can close positions you wanted to keep or leave you less protected than you think, there is a real risk of loss on every position it touches, and no output here is a promise of return. Curated by Skill Harbor: the IB stop-loss manager of staskh/trading_skills. Use it to manage downside stops on PMCC diagonal spreads, naked LEAPS and plain stock positions held at Interactive Brokers. The script computes a stop price per position (basis times one minus the stop percentage, 40 percent by default, the basis being the higher of mid price and average cost unless forced mode uses the current mid), classifies each position as pmcc, leaps or stock, and reports the action per position: place a new stop, preserve a more protective existing stop, or overwrite in forced mode. For a PMCC the stop is a single conditional combo (BAG) order that closes the LEAPS and all the short legs atomically, identified as SL_FALL orders, and orphan stops for gone positions are flagged, then cancelled in execute mode. The report leads with the alert-soon symbols (loss at or beyond half the stop percentage) and groups the alerts: LEAPS early warning, short premium 90 percent decayed (close or roll), and...

- Listing: https://theskillharbor.com/products/ib-stop-loss
- Fiche en français: https://theskillharbor.com/fr/products/ib-stop-loss
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib-stop-loss/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

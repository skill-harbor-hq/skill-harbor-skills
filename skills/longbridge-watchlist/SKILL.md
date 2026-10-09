<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: longbridge-watchlist
description: "Manage watchlist groups, price alerts, and community stock lists on your real Longbridge account..."
---

# Longbridge Watchlist and Alerts

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill changes data on your real brokerage account, so read every preview before you confirm it. Curated by Skill Harbor: the watchlist skill of the Longbridge platform, published by the broker itself, and the one skill in this family that writes instead of only reading. Through the Longbridge CLI it manages watchlist groups (list, create, rename, delete, add or remove symbols), price alerts (list, add, delete), and community stock lists or sharelists (list, detail, create, delete, manage members). Every operation requires you to be signed in with the CLI auth login, with at least quote permission on the account. Because these operations mutate real account data, the skill itself enforces a dry-run protocol for anything that creates, renames, deletes, adds or removes: it must first describe the planned action and what will change, then wait for your explicit confirmation, then execute, then report what was done, and it is written to ask rather than assume when intent is ambiguous. Its scope stops at lists and alerts: it places no orders and moves no money. From the longbridge/skills repository (MIT). Honest caveats: the confirmation protocol lives in the skill text, so it protects you only as long as you keep it and actually read the previews; a deleted group or alert is gone from your account, and the safe habit is to list the current state first and confirm each change one at a...

- Listing: https://theskillharbor.com/products/longbridge-watchlist
- Fiche en français: https://theskillharbor.com/fr/products/longbridge-watchlist
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/longbridge/skills/blob/main/skills/longbridge-watchlist/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

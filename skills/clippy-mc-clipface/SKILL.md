<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: clippy-mc-clipface
description: "Your AI, now a savvy shopper."
---

# McClipFace

⚠️ Privacy warning: coupon lookups send store, product name and currency to McClipFace, even in Private Mode. Your IP is not sent as lookup data. Nothing is sent during installation: the first contact with McClipFace happens at your first search.

Developer detail: the connection IP is processed server-side using a rotating keyed hash, for rate limiting only, and is not stored with individual searches or used to maintain per-user shopping histories.

New in version 2.9.1 (October 2026): the opt-in questions are gone — when you ask to buy, Muse checks McClipFace and tries codes as part of that request, with no question first, and new store visits open through McClipFace's affiliate link by default; a purchase still always needs your explicit approval of the item, the total and the payment. All of this is disclosed in the install prompt before anything is installed.

McClipFace finds your AI coupon codes automatically. When Muse shops for you, it gets codes from McClipFace before it picks a store and again before checkout, and when a store has no code right now, Muse keeps shopping. Free with no account or API key, and McClipFace never buys anything. Affiliate: McClipFace may earn a commission.

- Listing: https://theskillharbor.com/products/clippy-mc-clipface
- Fiche en français: https://theskillharbor.com/fr/products/clippy-mc-clipface
- Category: E-commerce
- Price: Free
- Verification: unverified
- Source repo: n/a

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

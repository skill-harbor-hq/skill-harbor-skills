<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: zhutoumeme-mcd-git-mcd-git
description: "Order McDonald's China with git style commands: add to a cart, rebase to save, commit to lock the..."
---

# mcd-git

A git flavoured command line for McDonald's China. The mcd-git tool wraps the McDonald's China MCP in commands you already know: init picks a store, add puts items in a cart (with customisations like no pickle, less ice or a swapped combo side), rebase rebuilds the cart into the cheapest valid combination of combos and coupons without adding anything, commit locks the order at a rechecked price, and push places it. Confirmation is enforced by the code, not just by instructions: push, revert (cancel) and pull (claim coupons) first return a preview summary and a next command carrying a confirmation hash or fingerprint, and the tool refuses to run the write if the parameters or the recomputed price no longer match the preview. It keeps its cart, order commits and a privacy trimmed local ledger on your machine, can show your pickup code, repeat a past order, and render a yearly McDonald's contribution card as a local SVG file. A --demo mode runs the whole flow on synthetic data with no token.

- Listing: https://theskillharbor.com/products/zhutoumeme-mcd-git-mcd-git
- Fiche en français: https://theskillharbor.com/fr/products/zhutoumeme-mcd-git-mcd-git
- Category: Food & Drink
- Price: Free
- Verification: unverified
- Source repo: https://github.com/zhutoumeme/mcd-git

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

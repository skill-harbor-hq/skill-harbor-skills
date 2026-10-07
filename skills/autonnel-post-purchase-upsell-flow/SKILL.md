<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: autonnel-post-purchase-upsell-flow
description: "One-click post-purchase upsells that lift average order value."
---

# Post-Purchase Upsell Flow Skill

Designs and implements one-click post-purchase upsells, cross-sells and downsells that raise average order value without risking the main conversion: complementary (not bigger) offers, one decision per screen, one-tap accept on stored payment credentials, honest easy decline, and a two-decision chain (upsell → optional upsell if accepted, downsell if declined). Covers the technical requirements that make one-click real — off-session charges, merged orders, deferred store/ERP push, per-charge refund tracking, idempotent accepts, SCA/3DS fallback — with Stripe and PayPal specifics, plus the guardrail metrics (take rate, AOV before/after, refund rate, unchanged base conversion). Discovered via skills.sh. Honest note: true one-click charging needs stored payment credentials and checkout support — most hosted funnel platforms gate it as a paid tier and most ecommerce checkouts can't do it without an app; the skill points to the self-hosted Apache-2.0 Autonnel project as the reference implementation; never ship a chain without an end-to-end paid test (test mode, then a real low-value order). Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/autonnel-post-purchase-upsell-flow
- Fiche en français: https://theskillharbor.com/fr/products/autonnel-post-purchase-upsell-flow
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/autonnel/autonnel-skills/blob/main/post-purchase-upsell-flow/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

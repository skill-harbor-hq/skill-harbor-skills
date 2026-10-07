<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: creator-outreach-kit
description: "Cold-outreach pipeline for open-source creators: find public emails, verify them, send personalized..."
---

# Creator Outreach Kit

The Creator Outreach Kit is the complete cold-email pipeline Skill Harbor used to contact 255 open-source creators about their listings, with a bounce rate under 4% after verification. It covers the whole chain, not just the sending: collect public GitHub emails for a list of creators, verify every address with a syntax check plus an MX/A DNS lookup (free, via dig), build a deduped send queue with one personalized message per creator, and send in daily batches with per-recipient claim links and an opt-out line in every message.

The kit ships with two working Python scripts. verify_emails.py takes your collected profiles and marks each address valid or not. send_batch.py sends the next N unsent queue entries through Gmail, marks them sent with a timestamp, and appends everything to send-log.txt. Both scripts share the same anti-placeholder guard that rejects scraper artifacts (name@email.com, your@email.com, u003e unicode escapes, fake domains) at queue-build time and again at send time, so a bad address can never slip through twice.

The operating rules are baked in: public emails only (never guess private addresses), one email per creator even for multiple projects, an opt-out in every message, no tracking pixels (developers notice), about 30 sends per day from a warmed-up mailbox, and a next-day bounce triage because a 200 OK on send is not proof of delivery. If your product has per-creator pages, the kit also documents the HMAC-signed, expiring claim-link pattern so a...

- Listing: https://theskillharbor.com/products/creator-outreach-kit
- Fiche en français: https://theskillharbor.com/fr/products/creator-outreach-kit
- Category: Marketing
- Price: Free
- Verification: verified
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

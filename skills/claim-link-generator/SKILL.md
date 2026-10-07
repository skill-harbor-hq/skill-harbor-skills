<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: claim-link-generator
description: "Let someone claim, edit, or take over their page with a magic link: no account, no password..."
---

# Claim-Link Generator

The Claim-Link Generator lets someone claim, edit, or take over their page with a magic link: no account, no password. One signed URL per recipient lets them take over their listing, edit the description, add links, and manage it themselves, with zero signup friction. It was proven across 255 creators with free, frictionless, expiry-bounded links.

The mechanism is simple and robust. The token is HMAC-SHA256 over a domain-separated payload: the literal prefix "claim." plus the lowercased email, a pipe, and a unix expiry timestamp, hex-encoded. The token carries email, expiry, and signature, so verification needs no database lookup for the signature check itself: the server recomputes the HMAC, compares in constant time, and rejects expired tokens. Thirty days of TTL is plenty; shorter for sensitive actions.

One token claims everything tied to that email (all their listings), not one token per item, which means fewer emails and fewer lost links. The claim page works with zero JavaScript because email recipients open links everywhere, and expired or tampered tokens show a plain "link expired" page with a resend option, never a stack trace.

The trust contract matters as much as the crypto: every claim email also offers the inverse ("rather not be listed? reply and I'll remove it"), because claim links build trust only when removal is one reply away. Tokens are bearer credentials, so they never go into logs, analytics URLs, or forwards, and the signing secret lives in a vault...

- Listing: https://theskillharbor.com/products/claim-link-generator
- Fiche en français: https://theskillharbor.com/fr/products/claim-link-generator
- Category: Developer Tools
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

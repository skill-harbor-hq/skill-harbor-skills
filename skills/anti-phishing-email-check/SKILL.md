<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: anti-phishing-email-check
description: "Verify a scary 'action required' email in 60 seconds: headers, link destinations, official-channel..."
---

# Anti-Phishing Email Check

The Anti-Phishing Email Check verifies whether a scary "action required" email is real or phishing before you click anything or share credentials. It is the five-minute triage from a real case: a "developer portal now open, complete the intake" email that turned out authentic (proper SPF, DKIM, and DMARC authentication, direct links, no redirectors) and would have been caught in sixty seconds if it had not been.

The workflow has five steps. First, read the headers: in Gmail, open the message and choose "Show original", then check Authentication-Results for spf=pass, dkim=pass, and dmarc=pass, all three, with the DKIM d= domain matching the claimed sender's domain rather than a lookalike. Second, inspect every link: the visible text means nothing, the real destination is the href. Red flags are URL shorteners, redirector domains, punycode and lookalike domains, and mismatched display versus destination. Third, check the ask: credential demands, password resets, payments, or "urgent" downloads deserve high alert, and legitimate senders rarely lead with urgency plus a link. When in doubt, do not use the email's link: navigate to the official site yourself and look for the same notice in your account. Fourth, cross-check the channel: a real "portal is open" email has a public counterpart on the company's site, status page, or verified social. Fifth, decide: authentic means proceed via your own navigation, suspicious means report as phishing and delete, and if you already...

- Listing: https://theskillharbor.com/products/anti-phishing-email-check
- Fiche en français: https://theskillharbor.com/fr/products/anti-phishing-email-check
- Category: Security
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

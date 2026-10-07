<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: private-rss-feed
description: "Serve a private RSS feed from a Cloudflare Worker: token-gated, 404-disguised, never a static file."
---

# Private RSS Feed

The Private RSS Feed serves a feed that must stay private: internal changelogs, subscriber-only updates, personal briefings. It is served live from a Cloudflare Worker, gated by a per-feed secret token, never as a static file and never linked with an autodiscovery link tag. A wrong or missing token gets a quiet 404, indistinguishable from "no feed here".

The handler reads ?token= from the query string, compares it against the secret stored in the worker's secrets table using a constant-time comparison, and returns 404 'Not found' as plain text on any mismatch. There is no "token exists but wrong" vs "no token" distinction: both are the same 404. A valid token builds the feed live from the database (latest N items, newest first, RFC-2822 dates, XML-escaped content) with a private Cache-Control header so shared caches never store a tokened feed.

Because the feed is private, it can carry subscriber-only lines a public feed never would, like yesterday-vs-day-before traffic or unpublished counts. These stay clearly useful and never sensitive. If the stats query errors, the feed still returns valid without the private line: fail-open on extras, never fail-closed on the feed itself.

Hygiene is the whole game: no static feed.xml in the build output (one deploy away from being public), no autodiscovery link tag, no token in URLs shared publicly. If the token leaks, you regenerate it with openssl rand -hex 32, update the secret store, redeploy (Pages binds secrets at deploy time)...

- Listing: https://theskillharbor.com/products/private-rss-feed
- Fiche en français: https://theskillharbor.com/fr/products/private-rss-feed
- Category: Web
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

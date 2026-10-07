<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: beta-gate
description: "Ship unfinished features to staging but never to production: a build-time flag plus a runtime guard."
---

# Beta Gate

Beta Gate is the two-layer system that keeps work-in-progress features visible on staging and impossible to serve in production. It was built for an Astro plus Cloudflare Pages site (the "Dry Dock") after a beta UI leaked to production through a normal deploy, and it has held ever since.

Layer one is a build-time flag. Every beta surface (nav link, homepage teaser, beta pages) is gated behind a single boolean read from the shell environment at build time. Build with SHOW_BETA=1 and the beta UI is included; build without it and the output contains zero beta HTML. The flag is read via process.env, not import.meta.env, because Vite does not inject arbitrary shell variables into import.meta.env. The flag module is imported from build-time code only, never from client-side scripts.

Layer two is a runtime guard in the worker entry. Before any route handling, requests to /beta* and /api/beta* on production hostnames get a plain 404. This catches the classic accident: a beta-enabled build deployed to production by mistake. Either layer alone would be enough on a careful day; together they make a leak practically impossible.

The kit also documents the deploy discipline that makes it stick: staging and prod as separate targets, never two builds at once (one build's output can clobber the other's), never rebuild the output directory while an upload is in flight, and a zero-tolerance post-build check that greps the prod output for beta path strings.

- Listing: https://theskillharbor.com/products/beta-gate
- Fiche en français: https://theskillharbor.com/fr/products/beta-gate
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

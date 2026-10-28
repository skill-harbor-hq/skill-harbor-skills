<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: recette-ssh-pc-portable
description: "Heavy jobs move to a portable PC, clean verdicts come back."
---

# Portable SSH PC Runner

Run a heavy test or a heavy treatment on a Windows PC you already connected, without installing anything in the system and without turning the PC into a publishing machine. The cloud assistant keeps planning and checking. The PC only supplies CPU, RAM and disk, through direct SSH, with portable tools that stay in one tools folder.

One job runs at a time, at least at first. A small job, a few seconds with the standard library only, stays on the cloud machine, because the SSH round trip would cost more than it gains. Before a big job, the skill checks that the PC answers, that no big job is already running, and that no deployment is in progress on the cloud side. Then it sends only what the job needs, by secure copy, into a test folder named for the job, never directly into the tools folder.

Paths are adapted before launch. No cloud machine path is left hard coded, separators and the remote interpreter are chosen explicitly, and a small sample is tested on the cloud machine first. The job launches with the full path of the portable tool, never by relying on the system PATH. For a browser test, the Playwright browsers path points to the portable browsers folder in the same launch. Versions are noted for every important job, because portable versions drift from the main account installs, and a test that passes on the PC must not be presented as proof for another environment without that check.

When the run ends, the verdict is copied back to the cloud machine and checked as...

- Listing: https://theskillharbor.com/products/recette-ssh-pc-portable
- Fiche en français: https://theskillharbor.com/fr/products/recette-ssh-pc-portable
- Category: Developer tools
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

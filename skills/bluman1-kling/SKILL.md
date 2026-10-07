<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-kling
description: "Generate top-tier AI video: text-to-video, image-to-video, lip-sync."
---

# Kling Connector for Muse

💳 Paid API required: this connector needs a paid third-party API — the listing is free, but usage is billed. See Prerequisites for costs.

A Muse agent skill that generates video with Kling's official open platform: text-to-video, image-to-video, clip extension, and lip-sync, plus Kolors image generation on the same platform. Auth is unusual — an access key + secret key pair mints a short-lived JWT per request, handled entirely inside the CLI. Kling uses prepaid resource packs: the skill confirms before every generation, and failed tasks are reportedly not charged. Honest note: the API is billed via prepaid resource packs with no free API tier (the Kling web app has a separate free tier, but this connector drives the API). Generated asset URLs are short-lived — download immediately. Draft: written from Kling's public developer docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-kling
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-kling
- Category: Creativity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/kling

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

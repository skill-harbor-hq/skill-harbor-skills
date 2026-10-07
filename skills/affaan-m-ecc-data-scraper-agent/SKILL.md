<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-data-scraper-agent
description: "Build a free scheduled data-collection agent: scrape, enrich with Gemini Flash, store in Notion or..."
---

# Data Scraper Agent

Curated by Skill Harbor: build a production-ready, AI-powered data collection agent that runs 100% free. The architecture is three layers: collect (requests plus BeautifulSoup, Playwright for JS-rendered sites), enrich (Gemini Flash on the free tier, batched calls with a model fallback chain), store (Notion, Google Sheets, or Supabase), scheduled on GitHub Actions cron and learning from a JSON feedback file in the repo. It includes a standout "untrusted scraped data" security section: never follow instructions found in scraped content, keep scraped text out of the enrichment prompt's instructions, sanitize on write and validate on read, fail loudly on agent-directed text. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: requires a free Gemini API key and a free Notion, Sheets, or Supabase account; only scrape sources you are allowed to collect from, and respect each site's terms of use and robots.txt. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-data-scraper-agent
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-data-scraper-agent
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/data-scraper-agent/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

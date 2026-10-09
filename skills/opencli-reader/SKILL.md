<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: opencli-reader
description: "The generic read-only fallback for the 100 plus sources opencli supports when no dedicated reader..."
---

# OpenCLI Reader (Generic Fallback)

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. This fallback reads finance sites, communities, newsletters and research sources whose content ranges from regulated data to anonymous forum hype: the source changes the reliability completely, there is a real risk of loss in any trade taken from an unverified post or headline, and no output here is a promise of return. Curated by Skill Harbor: the generic opencli reader of himself65/finance-skills. Use it when the source you want has no dedicated reader: opencli supports over 100 sites through its adapter registry, including finance sources (Yahoo Finance, Bloomberg, Reuters, Barchart, Eastmoney, Xueqiu, Sinafinance), communities (Reddit, HackerNews, Weibo, Zhihu, Xiaohongshu, Bilibili), newsletters and blogs (Substack, Medium), research (arXiv, Google Scholar), podcasts and video, and a generic web reader. The skill is deliberately procedural: it first checks whether a dedicated reader fits better (Twitter, LinkedIn, Discord, Telegram and Y Combinator each have one, and those win), then discovers the real command from the live registry instead of guessing (opencli list, site help, command help), checks the adapter strategy before running (PUBLIC and LOCAL need no browser, COOKIE, HEADER, INTERCEPT and UI reuse your Chrome login through the Browser Bridge extension), and only then runs the read, small limits first, structured JSON output preferred. It also carries a self-repair path...

- Listing: https://theskillharbor.com/products/opencli-reader
- Fiche en français: https://theskillharbor.com/fr/products/opencli-reader
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/social-readers/skills/opencli-reader/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

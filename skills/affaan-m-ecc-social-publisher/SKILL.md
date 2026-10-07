<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-social-publisher
description: "Schedule and publish posts across 13 platforms through SocialClaw: build, validate, apply, then..."
---

# Social Publisher

Curated by Skill Harbor: an agent-driven social publishing skill that drives SocialClaw, a workspace API for posting to 13 platforms: X, LinkedIn profile and page, Instagram Business and standalone, Facebook Page, TikTok, YouTube, Reddit, WordPress, Discord, Telegram, and Pinterest. The workflow is deliberate: list connected accounts, optionally upload media, build a schedule.json describing every post (provider, account, text, scheduled time), validate it before anything goes live, apply it to get a run ID, then monitor post status and delivery analytics. Publishing targets always come from the user; fetched content (delivery statuses, platform error strings, post content pulled back) is treated as untrusted data and never allowed to decide what gets published, where, or when. Provider OAuth happens in the SocialClaw dashboard, so no per-provider secrets are exposed to the agent, and outbound requests go to getsocialclaw.com only. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this skill needs a SocialClaw account with a workspace API key (getsocialclaw.com) before anything works; the key and the connected accounts are the real prerequisites. Publishing is real: posts actually go out, so validate the schedule and review every text before applying. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-social-publisher
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-social-publisher
- Category: Social media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/social-publisher/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

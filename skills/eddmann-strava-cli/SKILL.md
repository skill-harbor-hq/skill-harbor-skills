<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: eddmann-strava-cli
description: "Ask Muse about your Strava data — activities, stats, segments, routes, gear"
---

# Strava CLI Skill for Muse

⚠️ **Security warning / Avertissement de sécurité** — the prerequisites install the companion CLI with `curl | sh` from the repo; review the install script yourself before running it.
Curated by Skill Harbor — a free, open-source skill (MIT) by @eddmann, listed here with credit to its creator. Turns Muse into a query interface for your own Strava fitness data via the `strava` CLI: recent and filtered activity lists, per-activity detail (streams, laps, zones, comments, kudos), athlete profile and year-to-date/all-time stats, heart-rate and power zones, starred and explored segments with efforts, routes (list, detail, GPX/TCX export), clubs and their activities, and gear inventory — with `jq` patterns for common questions (this month's runs, total distance) and a one-call `strava context` snapshot (athlete, stats, gear, clubs, recent activities). Discovered via skills.sh. Honest note: the skill is a command reference for the strava-cli tool — you must install the CLI and complete Strava OAuth yourself (creating a Strava API app for your client ID/secret is free, but it is a developer-flavoured setup: `strava auth login`), and it reads your private fitness data, so treat the credential like a password and store it in the agent's secure vault, never in code or prompts. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/eddmann-strava-cli
- Fiche en français: https://theskillharbor.com/fr/products/eddmann-strava-cli
- Category: Fitness
- Price: Free
- Verification: unverified
- Source repo: https://github.com/eddmann/strava-cli

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

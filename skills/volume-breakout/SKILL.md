<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: volume-breakout
description: "Is that breakout real? A state machine checks the close, the volume, and the follow-through before..."
---

# Volume Breakout

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Most breakouts fail, and a framework that labels them carefully still cannot tell you which one will run. Curated by Skill Harbor: a breakout validation workflow from the Weaxs stock-analysis-plugin. It first pins down the resistance that matters (the 60-day high, a platform ceiling, the MA60 or MA120 overhead, the upper Bollinger band, a round number), then walks the move through four states instead of declaring victory on one strong candle: Setup (a clear level with volatility and volume contracting into it), Trigger (a close through the level on expanding volume and range), Acceptance (later closes holding above, a retest that does not break down on volume, relative strength intact), and Failure (a close back inside the range or heavy selling against the move). The output is a trade plan with one chosen trigger style, an invalidation level, a time stop, a target from the next resistance or the measured range, and the resulting reward-to-risk, plus the data gaps and the conditions under which the right move is to not trade. From the Weaxs/stock-analysis-plugin repository (MIT). Honest caveats: the source SKILL.md is written in Chinese; the fixed thresholds traders often quote (a volume ratio, a percentage gain) are treated here as market-specific parameters to backtest, not as universal constants, which is honest but means you must calibrate them yourself; an intraday poke above...

- Listing: https://theskillharbor.com/products/volume-breakout
- Fiche en français: https://theskillharbor.com/fr/products/volume-breakout
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Weaxs/stock-analysis-plugin/blob/main/skills/volume-breakout/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

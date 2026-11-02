<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: trader-timemachine
description: "Replay every outcome of a trade before you risk a dollar."
---

# trader-timemachine

Trader Timemachine sits between the plan and the money. It takes trader/plan.json from trader-exit, symbol, date, entry, entry time or entry bar, stop, stop rule, target, target R and opening range, or the same plan passed as flags. It keeps only full sessions before the plan's date: all 78 five-minute bars, 9:30 to 4:00 New York time. Half days, gaps and today are left out. For each replay it starts at the entry price, picks a past bar from the same time of day, plus or minus 2 bars, at random for each bar left in the day, scales it to the current price, and checks the stop first, then the target. A bar that touches both counts as the stop.

The 10,000 replays give four odds: target first, stop first, neither, meaning still open at the flat-by time, and green, meaning target first or above the entry at that time. They also give the price at the close, median and 5 to 95 range, and the average R. The history runs the plan's own rule on every past session, which is what really happened, not a simulation. The verdict is one line from the numbers: it looks only at replays that hit one side and asks how often the target came first, against the break-even rate for that R, 50 percent at 1R, 33 percent at 2R, 25 percent at 3R. The seed is 19 by default, and it must be stated with every result so any run can be repeated.

Limits as written in the SKILL.md: it is a simulation built from the stock's own recent bars, not a prediction. A good-looking replay does not change the fact that...

- Listing: https://theskillharbor.com/products/trader-timemachine
- Fiche en français: https://theskillharbor.com/fr/products/trader-timemachine
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Jakeschincariol/day-trader-skill

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

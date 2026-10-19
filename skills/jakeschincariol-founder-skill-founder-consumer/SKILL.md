<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: jakeschincariol-founder-skill-founder-consumer
description: "Test your pitch on 100 simulated buyers and learn who buys, who passes, and why."
---

# Founder Consumer

The consumer panel. From a target customer profile you approve first (founder/customer.json, with segments, incomes, buying behaviours and objections) and one pitch every buyer sees word for word (founder/pitch.md), the bundled tool panel.py deals reproducible persona cards (same seed, same cards) and writes one brief per buyer. The agent then runs one sub-agent per buyer, in waves of 10: 100 buyers by default, 20 with --quick. Each buyer answers in a fixed JSON shape: buys or not, purchases in the first month, the reason in their own voice, their main objection, what would change their mind, and four price answers that feed founder-pricing. panel.py checks the answers and tallies them into founder/panel/results.md: the buy rate, who buys and who passes by segment and behaviour, the top reasons people pass with quotes, and what would flip a no. The file is explicit about the limits: these are simulated buyers, language models lean agreeable, so the buy rate is an upper bound, not a forecast, and panel quotes are research, never testimonials.

- Listing: https://theskillharbor.com/products/jakeschincariol-founder-skill-founder-consumer
- Fiche en français: https://theskillharbor.com/fr/products/jakeschincariol-founder-skill-founder-consumer
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Jakeschincariol/founder-skill/blob/main/skills/founder-consumer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

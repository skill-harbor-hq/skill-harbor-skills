<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: trader-analyst
description: "Read earnings straight from SEC filings, quarter by quarter."
---

# trader-analyst

Trader Analyst answers two questions before a trade around earnings: what did the last report say, and is the next report inside this trade? Its tool, facts.py, uses only the Python standard library and needs no keys. It reads the XBRL company facts API, the company's submissions list for the newest 10-Q or 10-K and the newest 8-K with item 2.02, "Results of Operations", and that 8-K's folder to find the press release, the EX-99.1 exhibit. With the metrics option it writes trader/metrics.json, one row per company, for notes or a spreadsheet.

The rules are: filed numbers first, with the press release used for context and a clear statement of which numbers came from where; compare like with like, growth against the same quarter a year earlier; say what is derived, since companies do not file a Q4 10-Q and the fourth quarter is the 10-K year minus the three quarters inside it, marked "derived", with derived EPS approximate; say when the data lags, when the newest 10-Q is later than the newest quarter in the facts; and flag one-offs, when net income is above operating income. Banks and insurers have no gross margin: blank, not zero. Earnings calls are summed up only when the user pastes a transcript, or the company's investor relations page has one. The next report date is not in SEC data, so it is looked for in trader-news headlines or on the investor relations page, with its source stated.

Limits as written in the SKILL.md: it never says a stock is cheap, expensive, a buy or...

- Listing: https://theskillharbor.com/products/trader-analyst
- Fiche en français: https://theskillharbor.com/fr/products/trader-analyst
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

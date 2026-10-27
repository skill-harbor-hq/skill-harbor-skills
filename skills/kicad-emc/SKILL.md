<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad-emc
description: "Catch common EMC failures before fabrication with 18 check categories and a severity-ranked risk..."
---

# EMC Pre-Compliance Analysis

Curated by Skill Harbor: the pre-fabrication safety net in the KiCad collection. It runs automated electromagnetic compatibility risk analysis on a KiCad PCB design using geometric rule checks, analytical emission formulas, and optional SPICE simulation. Eighteen check categories and 44 rule identifiers cover ground planes, decoupling, input and output filtering, switching harmonics, clock routing, differential pair skew, board edge radiation, power distribution impedance, return paths, crosstalk, electrostatic discharge protection, shielding, and magnetic leakage from switching inductors. The output is a severity-ranked risk report with a pre-compliance test plan, framed against FCC Part 15, CISPR 32, CISPR 25 for automotive, and MIL-STD-461G. By @aklofas, listed here with credit to its creator. Honest caveats, stated plainly in the skill itself: this is a risk analyzer, not a compliance predictor. It catches roughly 70 percent of common EMC design mistakes before fabrication, but it cannot guarantee compliance, only a calibrated measurement in an accredited lab can do that. A SPICE simulator is optional, it only adds SPICE-enhanced checks. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad-emc
- Fiche en français: https://theskillharbor.com/fr/products/kicad-emc
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/emc

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

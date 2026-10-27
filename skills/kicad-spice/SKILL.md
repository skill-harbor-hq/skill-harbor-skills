<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kicad-spice
description: "Auto-generate and run SPICE testbenches for KiCad subcircuits, with a structured pass, warn and..."
---

# SPICE Simulation

Curated by Skill Harbor: the simulation skill in the KiCad collection, and a useful inversion of the usual simulation workflow. Instead of asking the user to build simulation sources and configure an analysis, it generates and runs SPICE testbenches automatically for subcircuits detected by the kicad skill's schematic analyzer: resistor-capacitor filters, inductor-capacitor filters, voltage dividers, opamp circuits and crystal oscillators. It validates calculated values, filter frequencies, divider ratios, opamp gains and crystal load capacitance, against actual simulation results, and produces a structured pass, warn and fail report. It supports ngspice, LTspice and Xyce, auto-detected, and it uses parametric data from the distributor skills for behavioral part models. By @aklofas, listed here with credit to its creator. Honest caveats: it works best paired with the kicad skill, which detects the subcircuits to simulate; a SPICE simulator must be installed on the machine, the skill does not install one; and simulation results validate a model of the circuit, not the built board, so real measurements still have the last word. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/kicad-spice
- Fiche en français: https://theskillharbor.com/fr/products/kicad-spice
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/aklofas/kicad-happy/tree/main/skills/spice

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

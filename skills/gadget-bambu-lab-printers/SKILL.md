<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gadget-bambu-lab-printers
description: "Check a Bambu Lab printer, its job, temperatures and filament, and send prints only through the LAN..."
---

# Bambu Lab Printers

Curated by Skill Harbor: a gadget skill for homes with a Bambu Lab printer (X1, P, A, or H series) bound to the owner's account. It starts from status, not from printing: job name, progress, remaining time, layers, nozzle and bed temperatures, and the AMS trays with filament type, color, and remaining amount, with a warning when a running job looks short on filament. Cloud status is the basic path; LAN status with the printer's access code is richer, with layers and temperatures the cloud view omits. Printing itself only works one way here, and the skill is blunt about it: Bambu signs cloud jobs with a private key, so no third party can send prints through Bambu Cloud at all. The only dispatch path is local, on printers where the owner has deliberately enabled LAN Only mode plus Developer Mode, with a file already sliced for the exact printer model and the user's explicit approval of that exact print. The skill also sets hard limits: pause, stop, or resume only on the owner's explicit request for that job, no camera view (there is no documented third-party live view), and firmware updates can change or close the paths it relies on. By @amanthakkar, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/gadget-bambu-lab-printers
- Fiche en français: https://theskillharbor.com/fr/products/gadget-bambu-lab-printers
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/amanthakkar/musecases/tree/main/skills/gadget-bambu-lab-printers

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

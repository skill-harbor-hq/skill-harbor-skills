<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mohitmishra786-low-level-dev-skills-openocd-jtag
description: "CMSIS-DAP/J-Link/ST-Link configs, GDB on extended-remote :3333, firmware flashing, hardware..."
---

# OpenOCD and JTAG/SWD debugging: flash firmware, attach GDB, set hardware breakpoints

Curated by Skill Harbor — @mohitmishra786's OpenOCD/JTAG skill: the complete agent workflow for embedded hardware debugging — JTAG vs SWD selection, OpenOCD interface configs for CMSIS-DAP, ST-Link, J-Link and FTDI adapters with target scripts (STM32, nRF52, ESP32, RP2040), connecting `arm-none-eabi-gdb` via extended-remote :3333 with reset-halt/load flows, firmware flashing via the ELF load path, the OpenOCD telnet program command, or script mode (`-c "program ... exit"`), hardware breakpoints (`hbreak`) and watchpoints (`watch`/`rwatch`/`awatch`) with their Cortex-M register limits, a monitor-command reference (reset, halt, mdw/mww, reg, disassemble), and a common-errors table with fixes (no JTAG device found, scan-chain failures, wrong flash driver, target-not-halted, memory-access errors) — plus the Segger JLinkGDBServer alternative. Honest caveats: it assumes physical access to the board, a working debug probe, and the correct `.cfg` for your exact MCU part number — it cannot fix a wrong target config for you; flashing real hardware is destructive by nature, double-check the image and address before running. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mohitmishra786-low-level-dev-skills-openocd-jtag
- Fiche en français: https://theskillharbor.com/fr/products/mohitmishra786-low-level-dev-skills-openocd-jtag
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mohitmishra786/low-level-dev-skills/blob/main/skills/embedded/openocd-jtag/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

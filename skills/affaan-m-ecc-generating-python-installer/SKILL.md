<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-generating-python-installer
description: "Commercial-grade Windows installers for Python apps: Nuitka extreme compilation, dist slimming, DLL..."
---

# Python Installer Builder (Nuitka)

Curated by Skill Harbor: commercial-grade Python deployment expertise for Windows, aiming at the smallest, fastest-starting, cleanest installer. The core approach is Nuitka folder mode (dist) plus Inno Setup packaging: no single-file builds, no stray console window. The workflow confirms build parameters first (app name, version, publisher, icon, never auto-filled), verifies the source build (console disabled, LTO enabled, VC++ runtime present), compiles with Nuitka using a module-exclusion and plugin strategy, slims the dist folder by stripping debug symbols, caches, tests and docs with safeguards for runtime-required metadata, analyzes DLLs to find and trim the largest dependencies including 32-bit vs 64-bit size tradeoffs, then packages with Inno Setup using LZMA2 ultra compression, full metadata, residue-free uninstall and an arch-matched VC++ redistributable. Includes a real production reference: a 323 MB PySide2 desktop app with OpenCV and Playwright, broken down dependency by dependency (71 DLLs, 93 MB) with the exact slimming moves that shrank it. From the affaan-m/ECC repository (MIT). Honest caveats: advanced size and startup optimization, not basic script-to-exe conversion; Windows only; some examples in the skill are written in Chinese. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-generating-python-installer
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-generating-python-installer
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/generating-python-installer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

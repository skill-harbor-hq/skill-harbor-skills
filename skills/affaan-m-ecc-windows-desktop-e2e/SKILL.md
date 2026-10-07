<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-windows-desktop-e2e
description: "End-to-end testing for Windows desktop apps (WPF, WinForms, Qt) with pywinauto and UI Automation..."
---

# Windows Desktop E2E Testing

Curated by Skill Harbor: end-to-end testing for Windows native desktop applications using pywinauto backed by Windows UI Automation. Covers WPF, WinForms, Win32/MFC, and Qt 5.x/6.x, with a UIA quality table per framework so you know what to expect before writing a line. The core discipline: give every interactive control a stable AutomationId first (x:Name in WPF, AccessibleName in WinForms, objectName in Qt), then locate by AutomationId, never by pixel coordinates. Ships a complete pytest suite layout: Page Object Model with a BasePage (locators, explicit waits, screenshot helpers), app-launch fixtures with failure screenshots, config via environment variables, and pytest.ini ready for CI. Goes deep on the hard parts: wait patterns that replace time.sleep, artifact management (screenshots, ffmpeg screen recording, opt-in per-step JSONL traces with PII redaction), flaky test triage with a cause-to-fix table, three tiers of test isolation (filesystem redirect, Windows Job Objects, full Windows Sandbox), and a GitHub Actions workflow for windows-latest runners. Qt gets its own section: enabling UIA in Qt 5.x, stable test IDs, QComboBox and QDialog quirks, plus a screenshot-mode fallback with OpenCV template matching for self-drawn controls. Use when writing or running E2E tests for a Windows desktop app, setting up a GUI suite from scratch, or diagnosing flaky desktop automation. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT)....

- Listing: https://theskillharbor.com/products/affaan-m-ecc-windows-desktop-e2e
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-windows-desktop-e2e
- Category: Testing
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/windows-desktop-e2e/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: forcedotcom-sf-skills-platform-apex-test-run
description: "Run Apex tests via sf CLI with a 120-point scoring rubric, high-signal rules (SeeAllData=false..."
---

# Apex test execution & coverage: disciplined run, score and fix loops for Salesforce tests

Curated by Skill Harbor — the official @forcedotcom skill for Apex test execution and coverage analysis: running tests, diagnosing failures, improving coverage, and managing a disciplined test-fix loop for Salesforce code. The workflow goes discover test scope → run the smallest useful set first → analyze (failing methods, exception types, uncovered lines, whether failures mean bad test data, brittle assertions, or broken production logic) → disciplined fix loop → intentional coverage improvement (positive, negative/exception, bulk with 251+ records to cross the 200-record trigger batch boundary, callout/async paths). High-signal rules: default to `SeeAllData=false` for test isolation, every test must assert meaningful outcomes, pair `Test.startTest()` with `Test.stopTest()` for async, never hide flaky org dependencies inside tests. Output format is fixed (what ran → pass/fail summary → coverage → root causes → fix or next-run recommendation), and every run is scored on a 120-point rubric (108+ = strong production-grade confidence, <84 = below standard). Ships with reference files (CLI commands, test patterns, best practices, fix-loop decision tree, mocking and performance guides), test-class templates (basic, bulk, mock callout, data factory, DML mock, StubProvider), and a `parse-test-results.py` hook script for the auto-fix loop. Delegates cleanly: production code to platform-apex-generate, LWC/Jest to experience-lwc-generate, Agentforce testing to agentforce-test. Honest...

- Listing: https://theskillharbor.com/products/forcedotcom-sf-skills-platform-apex-test-run
- Fiche en français: https://theskillharbor.com/fr/products/forcedotcom-sf-skills-platform-apex-test-run
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/forcedotcom/sf-skills/blob/main/plugins/builder/salesforce-development/skills/platform-apex-test-run/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

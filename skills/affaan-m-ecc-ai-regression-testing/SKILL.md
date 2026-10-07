<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-ai-regression-testing
description: "Catch the blind spots when AI writes and reviews its own code: sandbox-mode API tests and bug-check..."
---

# AI Regression Testing

Curated by Skill Harbor: testing patterns built for AI-assisted development, where the same model writes code and reviews it, carrying the same assumptions into both steps. The skill names the core failure pattern with a real production example: a fix passes the AI's own review four times while the bug survives, because sandbox and production code paths drift apart unnoticed. The answer is sandbox-mode API testing without database dependencies (with a Vitest plus Next.js App Router setup as the worked example), automated bug-check workflows to run after every AI change, and regression coverage aimed specifically at AI blind spots: the paths the model touched, the flags it toggled, the inconsistency between the mode it tested and the mode users hit. Activate it whenever an AI agent modifies API routes or backend logic, when a fixed bug must stay fixed, or when running a bug-check pass after code changes. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: the sandbox-testing approach works best on projects that already have a mock or sandbox mode; without one, you test against the real database or you build the seam first. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-ai-regression-testing
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-ai-regression-testing
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/ai-regression-testing/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

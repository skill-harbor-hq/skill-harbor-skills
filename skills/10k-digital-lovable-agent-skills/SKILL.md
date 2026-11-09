<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: 10k-digital-lovable-agent-skills
description: "Drive your Lovable project from Muse: sync, deploy, migrate, test."
---

# Lovable Agent Skills for Muse

Lovable Agent Skills lets Muse work on your Lovable project instead of only describing it. Eight skills cover the loop: project setup, GitHub sync, edge-function deploys, migrations, and testing, with Lovable's exact prompts for the backend. Lovable is a large platform (about 8M users, 100,000+ new projects a day) — this plugin is the bridge between it and Muse.

The guardrails are real and readable in the code. YOLO mode is off by default and never enables auto-push on its own; confirmation is always kept for destructive database work; `deploy.confirm_migrations` is honoured even in YOLO; auto-push runs only if you explicitly turn it on.

Caveats:
- Lovable-side actions (deploy, migrations, preview tests) need a Lovable account + credits — **never tested here** (account + credits required).
- The git hooks run automatically when the plugin is loaded: sync at session start (`git pull --rebase` on main only, never with uncommitted changes), push at stop only if auto-push is explicitly enabled.
- Install via the Claude Code marketplace or local copy was not tested in Claude Code (no Claude Code on the test PC); `migrate-workspace.py` was not tested on a real project.

- Listing: https://theskillharbor.com/products/10k-digital-lovable-agent-skills
- Fiche en français: https://theskillharbor.com/fr/products/10k-digital-lovable-agent-skills
- Category: Developer tools
- Price: Free
- Verification: verified
- Source repo: https://github.com/10K-Digital/lovable-agent-skills

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: takeover
description: "Finish someone else's work, with their credit intact."
---

# takeover

For a replacement PR, takeover imports the original commits onto a new branch and adds its fixes separately, honoring an explicitly requested in-place or stacked continuation instead. It does not overwrite unrelated work or change the original PR without authorization. It preserves Git authorship and existing co-author trailers, credits the original contributors in the PR description, and links the original PR when there is one. If the work will be squashed, human author and co-author credit is preserved in the merge commit too, using verified identities rather than guessed emails. Model attribution is not a substitute for contributor credit.

It uses modernize to update the continuation against its intended base and current architecture. It reworks what is necessary to finish the same goal, not unrelated features, and simplifies the implementation without dropping intended behavior or surfaces. It rechecks the source PR too, since it may have improved while the takeover was in progress. It independently verifies the original failure and realistic workflows, following repository guidance and permissions. Green mocked tests do not prove the user experience works, so it states what remains unverified.

Limits as written in the SKILL.md: when the requested finish includes a PR, use file-pr to file or update it, then babysit-pr rather than stopping at creation, and use leaving-pr-comments for replies. Merge or close the original PR only when authorized. The report covers what...

- Listing: https://theskillharbor.com/products/takeover
- Fiche en français: https://theskillharbor.com/fr/products/takeover
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/t3dotgg/tstack

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

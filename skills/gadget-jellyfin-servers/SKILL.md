<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gadget-jellyfin-servers
description: "See what is playing and search a self-hosted Jellyfin library, with playback control only on..."
---

# Jellyfin Servers

Curated by Skill Harbor: a gadget skill for homes that already run a self-hosted Jellyfin media server, typically on a Raspberry Pi or home server, where the library of the house lives in one place. It answers three kinds of questions from the server's own API instead of scraping a client app: what is playing right now, with each active session's user, client and device, title, and position against runtime; what is in the library, searched as a scoped user so answers inherit that user's library access and parental controls; and, only on explicit request, playback control on an agreed client, pause, resume, stop, next, previous, or starting an item. The setup honesty matters here: the owner picks a dedicated, limited, non-admin Jellyfin user for the skill, because a Jellyfin API key is server-wide and effectively administrative, so the limited user's token is the safer default, and either credential is a secret, never pasted into chat, a skill file, or a repo. The server stays local with no port-forwarding, and a session is treated as live data: the skill confirms the target session by its current title immediately before sending a command, since the living-room session from an hour ago may be a different device now, and it re-reads after every command, because a success response is not proof the client acted. It never administers the server: no deletes, no library scans, no metadata edits, no user or configuration changes, and viewing history is household data, reported for...

- Listing: https://theskillharbor.com/products/gadget-jellyfin-servers
- Fiche en français: https://theskillharbor.com/fr/products/gadget-jellyfin-servers
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/amanthakkar/musecases/tree/main/skills/gadget-jellyfin-servers

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

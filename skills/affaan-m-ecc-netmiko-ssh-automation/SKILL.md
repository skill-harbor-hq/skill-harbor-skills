<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-netmiko-ssh-automation
description: "Safe Python Netmiko patterns for network devices: read-only collection first, bounded batch SSH..."
---

# Netmiko SSH Automation

Curated by Skill Harbor: a Netmiko SSH automation skill that teaches Muse to automate network devices without taking the network down. The safety defaults are the whole point: start with read-only `send_command()` collection, keep the inventory small and explicit (no sweeping whole address ranges), pull credentials from environment variables, a vault, or `getpass` (never hardcoded), set connection and read timeouts, limit concurrency so older devices are not overloaded, require an explicit operator flag before any `send_config_set()`, and never call `save_config()` until the change is verified and approved. It covers TextFSM parsing for structured output, Netmiko exception handling (authentication, timeouts, read timeouts), and bounded batch SSH patterns for collecting `show` output across routers, switches, and firewalls. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this skill drives real SSH sessions against real devices; review every script before it touches production; start read-only and promote to config changes only with explicit approval. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-netmiko-ssh-automation
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-netmiko-ssh-automation
- Category: Networking
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/netmiko-ssh-automation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

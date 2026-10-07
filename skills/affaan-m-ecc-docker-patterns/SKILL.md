<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-docker-patterns
description: "Docker and Compose patterns for local dev stacks, hardened Dockerfiles, networking, volumes, and..."
---

# Docker Patterns

Curated by Skill Harbor: Docker and Docker Compose best practices for containerized development. The centerpiece is a complete local development stack in Compose: an app service built from the dev stage of a multi-stage Dockerfile with bind mounts for hot reload, a Postgres service with health checks and init scripts, and Redis, wired with depends_on conditions so services start in the right order. Beyond the happy path it covers hardened Dockerfiles, container security basics, networking between services, volume strategies (bind mounts for code, named volumes for data, anonymous volumes to preserve container dependencies), and multi-service orchestration. It also addresses the less glamorous side: building hardened CLI installer harnesses and testing installers across Linux distributions, plus planning accurate native validation on macOS and Windows where containers behave differently. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: the hands-on parts assume Docker is installed and running on your machine; examples lean toward Node.js and Postgres but the Compose patterns transfer to any stack. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-docker-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-docker-patterns
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/docker-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

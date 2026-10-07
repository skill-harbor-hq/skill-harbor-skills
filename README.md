<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
# skill-harbor-skills

Machine-readable mirror of the **Skill Harbor** catalog: every listing as a `SKILL.md` file, generated from [https://theskillharbor.com](https://theskillharbor.com).

Skill Harbor is the open directory of AI builds for Muse (bilingual EN/FR). This repo exists so that AI agents and indexers can discover the catalog where they already look: on GitHub.

## Layout

- `skills/<slug>/SKILL.md` — one file per listing (name, one-line description, link to the live listing, install pointer).
- `SKILL.md` (root) — `skill-harbor-discovery`: instructions teaching an AI agent how to find a build on Skill Harbor.

## Freshness

Regenerated from the live catalog on a regular basis. The listing pages on https://theskillharbor.com are always the source of truth; treat anything here that disagrees with the site as stale.

## Install model

Skill Harbor installs are copy-paste: open the listing page, copy the install package, paste it into Muse. There is no `npx`/CLI install path.

## Links

- Catalog: https://theskillharbor.com/products
- Public search API (no key): `GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10`
- MCP: `POST https://theskillharbor.com/mcp` (tools: `search_builds`, `get_build`, `get_install`)

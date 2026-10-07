<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-regex-vs-llm-structured-text
description: "Cheap document parsing for Muse: a regex-first pipeline that handles 95%+ of structured text, with..."
---

# Regex vs LLM for Structured Text

Curated by Skill Harbor: a decision framework and hybrid pipeline for parsing structured text that keeps Muse from burning money on LLM calls regex could have handled. The key insight: regex handles 95-98% of cases cheaply and deterministically, reserve expensive LLM calls for the remaining edge cases. Architecture: a regex parser extracts structure first, a text cleaner removes noise (markers, page numbers, artifacts), a confidence scorer flags low-confidence extractions (few choices, missing answer, short text), and an LLM validator fixes only the flagged items, returning corrected JSON or CORRECT. Includes a complete Python implementation (frozen dataclasses, never mutate parsed items), real-world metrics from a production quiz pipeline (410 items: 98.0% regex success, 8 low-confidence items, about 5 LLM calls, ~95% cost savings versus all-LLM, 93% test coverage), a decision tree (consistent repeating format goes regex-first, free-form variable text goes LLM directly), best practices (start with regex even imperfect, cheapest Haiku-class model for validation, TDD for parsers, log pipeline metrics), and anti-patterns to avoid (sending everything to an LLM, regex for free-form text, skipping confidence scoring, mutating parsed objects). Use when parsing quizzes, forms, invoices, receipts or tables, choosing between regex and LLM for extraction, or optimizing extraction cost and accuracy. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-regex-vs-llm-structured-text
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-regex-vs-llm-structured-text
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/regex-vs-llm-structured-text/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: claude-office-skills-skills-batch-processor
description: "Convert, transform, extract or analyze hundreds of files with parallel execution, progress bars..."
---

# Batch document processor with parallel workers and resume checkpoints

Curated by Skill Harbor — @claude-office-skills' bulk document-processing skill: convert, transform, extract or analyze hundreds of files with parallel execution and progress tracking. The core is a ready-to-adapt Python pattern — `ProcessPoolExecutor` fan-out over a glob of files with `tqdm` progress bars, per-file result/error records, plus a `BatchProcessor` class with a JSON checkpoint file so long jobs skip already-processed files and resume after interruption. Best practices: progress bars for user feedback, checkpointing for long jobs, worker counts matched to CPU cores, logging failures for later review. Example tasks: convert 100 PDFs to Word, extract text from all images in a folder, batch rename and organize files, mass-update document headers/footers. Installation notes a `pip install python-docx openpyxl python-pptx reportlab jinja2`. Honest caveats: the SKILL.md header references an `office-mcp` MCP server (`batch_convert`) that likely does not exist in your setup — the reusable value here is the prompt guide and the Python code, not that integration; works in English and Chinese. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/claude-office-skills-skills-batch-processor
- Fiche en français: https://theskillharbor.com/fr/products/claude-office-skills-skills-batch-processor
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/claude-office-skills/skills/blob/main/batch-processor/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

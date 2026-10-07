<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: orchestra-research-ai-research-skills-knowledge-distillation
description: "Temperature scaling and soft targets, forward vs reverse KLD (MiniLLM), logit and response..."
---

# Knowledge distillation for LLMs: compress teachers into small capable students

Curated by Skill Harbor — @orchestra-research's knowledge-distillation skill: the complete workflow for compressing large LLMs into smaller deployable models — temperature scaling (T=2-5 standard), soft vs hard loss combination (alpha weighting), forward vs reverse KL divergence (MiniLLM's reverse KLD for mode-covering generative quality), logit distillation (direct and MSE variants), response distillation (train on teacher-generated synthetic data), two-stage and multi-teacher strategies, a ready-to-adapt basic-distillation training loop, a production `DistillationTrainer` (transformers Trainer subclass with distillation loss), hyperparameter rules (size ratios: 10x excellent like 70B→7B, avoid 70x gaps), data-quality guidance (70% teacher-generated + 30% real), and an evaluation pattern comparing teacher vs student outputs. Paper references: Hinton et al. 2015, MiniLLM, the 2024 KD survey. Honest caveats: the headline claim (70B→7B retaining 90%+ performance) is the skill's — real results vary by task and data; distilling from proprietary models (GPT-4) raises terms-of-service and licensing questions — check the teacher's terms before distilling; needs substantial GPU compute for training. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/orchestra-research-ai-research-skills-knowledge-distillation
- Fiche en français: https://theskillharbor.com/fr/products/orchestra-research-ai-research-skills-knowledge-distillation
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/orchestra-research/ai-research-skills/blob/main/19-emerging-techniques/knowledge-distillation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

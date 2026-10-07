<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-pytorch-patterns
description: "Idiomatic PyTorch: device-agnostic code, reproducible training loops, efficient data loading, and..."
---

# PyTorch Patterns

Curated by Skill Harbor: idiomatic PyTorch patterns for building robust, efficient, and reproducible deep learning applications. Three core principles: device-agnostic code (never hardcode .cuda(), always route through a device variable), reproducibility first (seed torch, CUDA, numpy, and random together, deterministic cuDNN), and explicit shape management with annotated tensor shapes in every forward pass. Covers clean nn.Module structure with explicit weight initialization (kaiming for Linear/Conv, ones/zeros for BatchNorm), complete training loops (mixed precision with GradScaler, gradient clipping, zero_grad(set_to_none=True)), proper validation (always model.eval() with torch.no_grad(), never leave dropout active), efficient DataLoader configuration (num_workers, pin_memory, persistent_workers, drop_last), custom datasets and collate functions for variable-length data, full checkpointing (model plus optimizer plus epoch state, weights_only=True for secure loading), and performance (AMP, gradient checkpointing trading compute for memory, torch.compile in PyTorch 2.0+). Includes an anti-pattern table: forgetting eval mode during validation, in-place ops breaking autograd, calling .item() before backward, moving the model to GPU inside the loop. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; you need Python with PyTorch installed, and a GPU to benefit from the performance...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-pytorch-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-pytorch-patterns
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/pytorch-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

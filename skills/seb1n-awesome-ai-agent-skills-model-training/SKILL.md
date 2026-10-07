<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: seb1n-awesome-ai-agent-skills-model-training
description: "A complete training lifecycle workflow — data loading and profiling, preprocessing pipelines..."
---

# Model Training — end-to-end ML training with checkpoints and tracking

Curated by Skill Harbor — @seb1n's model-training skill, listed here with credit to its creator: a complete training-lifecycle workflow that lets an agent train machine-learning models end to end — loading and profiling data (feature distributions, class balance, missing values), stratified train/validation/test splits, reproducible preprocessing pipelines (normalization, tokenization, augmentation) serializable for inference, architecture selection (gradient boosting/SVMs for classical ML; PyTorch/TensorFlow layers with dropout and weight decay for deep learning; pre-trained backbones for transfer learning), training configuration (Adam/SGD/AdamW, cross-entropy/MSE/focal loss, cosine/step/warmup schedules, mixed precision with torch.amp), training loops with validation and early stopping, checkpointing of the best validation score, and export to portable formats (ONNX, TorchScript, SavedModel), with hyperparameters and metrics logged to MLflow or Weights & Biases. It ships worked examples: a PyTorch text classifier (LSTM, cosine annealing, early stopping, best_model.pt) and a Hugging Face Transformers fine-tuning recipe. Honest caveats: training consumes real compute (GPU time costs money — start with the small deterministic fixture it suggests); the examples train on simulated data, so adapt them to your own datasets; exported artifacts and hyperparameters can leak training-data details — keep them in a registry with proper access controls. MIT licensed. Skill Harbor never...

- Listing: https://theskillharbor.com/products/seb1n-awesome-ai-agent-skills-model-training
- Fiche en français: https://theskillharbor.com/fr/products/seb1n-awesome-ai-agent-skills-model-training
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/seb1n/awesome-ai-agent-skills/blob/main/ai-ml-operations/model-training/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`

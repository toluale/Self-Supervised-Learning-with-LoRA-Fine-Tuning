# Self-Supervised-Learning-with-LoRA-Fine-Tuning

This notebook demonstrates a complete pipeline for:
1. **Self-Supervised Learning (SSL)** - Pre-training a model using denoising autoencoder
2. **LoRA (Low-Rank Adaptation)** - Parameter-efficient fine-tuning
3. **Evaluation** - Comparing SSL+LoRA against baseline models

## Approach Overview
- **Phase 1**: SSL pre-training on CNN/DailyMail dataset using denoising autoencoder
- **Phase 2**: LoRA fine-tuning on DialogSum dataset with minimal labeled data
- **Phase 3**: Evaluation using ROUGE, BLEU, and BERTScore metrics

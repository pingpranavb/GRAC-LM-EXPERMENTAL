# GRAC-LM-EXPERMENTAL
GRAC-LM is GRC's independently developed GPT-style language model research project, focused on transformer architecture, training from scratch, instruction tuning, evaluation, and future foundation-model development.
# GRAC-LM

### Independent Language Model Research by GRC

GRAC-LM is an experimental GPT-style decoder-only Transformer language model independently developed and trained as part of the GRC AI Programme.

The project focuses on understanding foundation-model engineering, including transformer architecture, tokenization, pretraining, instruction tuning, generalization, and evaluation.

## GRAC-LM v0.4

| Specification | Value |
|---|---|
| Architecture | Decoder-only Transformer |
| Parameters | Approximately 54.7 million |
| Vocabulary | 8,000 tokens |
| Context length | 512 tokens |
| Transformer layers | 10 |
| Attention heads | 10 |
| Embedding dimension | 640 |
| Training hardware | NVIDIA Tesla T4 (Google Colab) |

## Research Progress

The GRAC-LM v0.4 research cycle concluded after Cell 81, following experiments in instruction tuning, factual learning, mixed-data training, and arithmetic generalization.

### Phase 4D Results

- Training: 250 optimizer steps
- QA validation loss: 2.5860 → 1.1796
- Sampled training accuracy: 10/120 (8.3%)
- Held-out validation accuracy: 3/59 (5.1%)
- Held-out test split: Not yet evaluated

The model demonstrated successful training and measurable improvements in token prediction loss. However, question-answering accuracy and generalization remained weak.

These results are documented to support transparent, reproducible research.

## Current Status

**GRAC-LM v0.4: Research cycle paused after Cell 81.**

The model is not production-ready and is not currently suitable for reliable general-purpose assistant use.

Model checkpoints are preserved separately in Google Drive.

## Future Development

GRAC-LM research will resume after the GRAC Assistant product is launched and stabilized.

Future work will focus on stronger pretraining, improved datasets, generalization, evaluation, and independent foundation-model development.

## GRAC Assistant

GRAC Assistant is a separate GRC AI product that will use an existing pretrained foundation model with GRC-directed fine-tuning and software development.

It does not replace GRAC-LM's independent research programme.

---

**GRC AI Programme | GRAC-LM v0.4 | Research archived October 8, 2026**

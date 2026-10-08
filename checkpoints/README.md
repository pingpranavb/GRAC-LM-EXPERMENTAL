
GUYS AND I ALSO CANT PROVIDE THE CHECKPOINTS, that is the .pt checkpoints private, because the GRAC-LM is not suitable for real use, and its validation accuracy is just 5.1%.


# GRAC-LM v0.4 — Trained Model Checkpoints

This directory documents the trained checkpoints produced during GRC's independent GRAC-LM v0.4 research.

## Checkpoint Inventory

| Phase | Checkpoint File |
|---|---|
| Phase 4 | `GRAC-LM-v0.4-expanded-best.pt` |
| Phase 4B | `GRAC-LM-v0.4-phase4b-step300.pt` |
| Phase 4C | `GRAC-LM-v0.4-phase4c-best.pt` |
| Phase 4D | `GRAC-LM-v0.4-phase4d-best.pt` |
| Phase 4D Resume | `GRAC-LM-v0.4-phase4d-resume.pt` |

## Storage

All five checkpoints were verified during Cell 81.

The original model files are preserved in Google Drive under:

`GRAC/GRAC-LM-v0.4/`

The checkpoint files are not currently distributed through this GitHub repository.

## Model Specifications

- Architecture: GPT-style decoder-only Transformer
- Parameters: approximately 54.7 million
- Vocabulary: 8,000 tokens
- Context length: 512 tokens
- Transformer layers: 10
- Attention heads: 10
- Embedding dimension: 640

## Research Status

**GRAC-LM v0.4 research paused after Cell 81 on October 8, 2026.**

Future research will resume after GRAC Assistant is launched and stabilized.

This repository will continue receiving updates as independent GRAC-LM development progresses.

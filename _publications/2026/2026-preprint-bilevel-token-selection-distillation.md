---
title:          "Learning What to Distill: Bilevel Top-K Token Selection for Self-Distillation in Large Language Models"
date:           2026-10-05 00:00:00 +0800
selected:       false
pub_date:       "2026"
pub_post:       'Preprint.'
preprint:       true
venue:          "arXiv preprint arXiv:2610.07247."
abstract: >-
  Large language models have shown strong reasoning capabilities, but their high inference costs make knowledge distillation an important approach for transferring such capabilities to compact models in resource-constrained scenarios. On-policy self-distillation further reduces the reliance on external large teacher models while improving the reasoning ability of compact language models. However, existing methods typically either distill all token positions uniformly or select tokens using fixed heuristic criteria, assigning the same distillation strength to the selected positions rather than adaptively learning which tokens are most beneficial for distillation. To address these limitations, we propose BiToK-SD (Bilevel Top-K Token Selection for Self-Distillation), a bilevel-optimization-based token selection method that learns where distillation should be applied during on-policy self-distillation. Specifically, BiToK-SD is formulated as a bilevel optimization problem, where the lower-level problem models Top-K token selection as a differentiable threshold-based relaxation, allowing the selected positions to adapt as the student policy evolves, while the upper-level problem performs knowledge distillation on the selected positions. Experiments on mathematical reasoning benchmarks show that BiToK-SD achieves the best average performance among all compared methods while requiring only lightweight additional computation.
authors:
  - Heng Liang
  - <strong>Xinwen Zhang</strong>
  - Hongchang Gao
links:
  Paper: https://arxiv.org/abs/2610.07247
---

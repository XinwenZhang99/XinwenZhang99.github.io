---
title:          "On the Convergence of Stochastic Smoothed Multi-Level Compositional Gradient Descent Ascent"
date:           2025-09-18 00:00:00 +0800
selected:       false
pub:            "Advances in Neural Information Processing Systems (NeurIPS)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  Multi-level compositional optimization is a fundamental framework in machine learning with broad applications. While recent advances have addressed compositional minimization problems, the stochastic multi-level compositional minimax problem introduces significant new challenges—most notably, the biased nature of stochastic gradients for both the primal and dual variables. In this work, we address this gap by proposing a novel stochastic multi-level compositional gradient descent-ascent algorithm, incorporating a smoothing technique under the nonconvex-PL condition. We establish a convergence rate to an $(\epsilon, \epsilon/\sqrt{\kappa})$-stationary point with improved dependence on the condition number at $O(\kappa^{3/2})$, where $\epsilon$ denotes the solution accuracy and $\kappa$ represents the condition number. Moreover,  we  design a novel stage-wise algorithm with variance reduction to address the  biased gradient issue under the two-sided PL condition. This algorithm successfully enables a translation from and $(\epsilon, \epsilon/\sqrt{\kappa})$-stationary point to an $\epsilon$-stationary point. Finally, extensive experiments validate the effectiveness of our algorithms.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - <strong>Xinwen Zhang</strong>
  - Hongchang Gao
links:
  # Code: https://github.com/luost26/bubble-visual-hash
  # Demo: https://luost26.github.io/bubble-visual-hash
---

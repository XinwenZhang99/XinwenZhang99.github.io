---
title:          "Smoothed Gradient Method for Nonconvex Federated Stochastic Bilevel Optimization"
date:           2026-10-04 00:00:00 +0800
selected:       false
pub_date:       "2026"
pub_post:       'Preprint.'
preprint:       true
venue:          "arXiv preprint arXiv:2610.05290."
abstract: >-
  In recent years, federated stochastic bilevel optimization has attracted increasing attention due to its wide range of applications in machine learning. To reduce the computational overhead associated with second-order Hessian and Jacobian matrices, several first-order methods have been proposed. However, existing methods typically impose restrictive assumptions on the lower-level function, suffer from a strong dependence on the condition number in their convergence rates, and require different learning-rate scales for variables across the upper- and lower-level problems, limiting their practical applicability and complicating hyperparameter tuning. To address these challenges, we propose a stochastic doubly smoothed gradient method for nonconvex federated stochastic bilevel optimization problems, which decouples the learning rates of upper- and lower-level variables and does not require a strongly-convex lower-level loss function. We establish rigorous theoretical guarantees for the proposed algorithm, demonstrating an improved convergence rate of $O(\kappa^{15/2}/\epsilon^5)$ and a communication complexity of $O(\kappa^{4}/\epsilon^3)$, where $\kappa$ denotes the condition number and $\epsilon$ represents the solution accuracy. Notably, these bounds exhibit significantly better dependence on the condition number $\kappa$ than those of existing methods. Extensive experiments validate the effectiveness of our algorithm.
authors:
  - <strong>Xinwen Zhang</strong>
  - Peiran Yu
  - Zhaosong Lu
  - Hongchang Gao
links:
  Paper: https://arxiv.org/abs/2610.05290
---

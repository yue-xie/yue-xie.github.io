---
title: "Randomized methods for computing optimal transport without regularization and their convergence analysis"
collection: publications
permalink: /publication/OT-JOMP
excerpt: ''
date: 2024-05-20
venue: 'Journal of Scientific Computing'
paperurl: 'https://arxiv.org/abs/2212.07046'
citation: 'Yue Xie, Zhongjian Wang and Zhiwen Zhang. &quot;Complexity of proximal augmented Lagrangian for nonconvex optimization with nonlinear equality constraints.&quot; <i>Journal of Scientific Computing</i>.'
---
## Abstract

We analyze worst-case complexity of a Proximal augmented Lagrangian (Proximal AL) framework for nonconvex optimization with nonlinear equality constraints. When an approximate first-order (second-order) optimal point is obtained in the subproblem, an ϵ first-order (second-order) optimal point for the original problem can be guaranteed within $\mathcal{O}(1/\epsilon^{2−\eta})$ outer iterations (where $\eta$ is a user-defined parameter with $\eta \in [0,2]$ for the first-order result and $\eta \in [1,2]$ for the second-order result) when the proximal term coefficient $\beta$ and penalty parameter $\rho$ satisfy $\beta = \mathcal{O}(\epsilon^\eta)$ and $\rho = \Omega(1/\epsilon^\eta)$, respectively. We also investigate the total iteration complexity and operation complexity when a Newton-conjugate-gradient algorithm is used to solve the subproblems. Finally, we discuss an adaptive scheme for determining a value of the parameter ρ that satisfies the requirements of the analysis.

[Find arXiv version here](https://arxiv.org/abs/2212.07046)
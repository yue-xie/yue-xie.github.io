---
title: "Randomized methods for computing optimal transport without regularization and their convergence analysis"
collection: publications
permalink: /publication/OT-JOMP
excerpt: ''
date: 2024-05-20
venue: 'Journal of Scientific Computing'
paperurl: 'https://arxiv.org/abs/2212.07046'
citation: 'Yue Xie, Zhongjian Wang and Zhiwen Zhang. &quot;Randomized methods for computing optimal transport without regularization and their convergence analysis.&quot; <i>Journal of Scientific Computing</i>.'
---
## Abstract

The optimal transport (OT) problem can be reduced to a linear programming (LP) problem through discretization. In this paper, we introduced the random block coordinate descent (RBCD) methods to directly solve this LP problem. Our approach involves restricting the potentially large-scale optimization problem to small LP subproblems constructed via randomly chosen working sets. By using a random Gauss-Southwell-q rule to select these working sets, we equip the vanilla version of (RBCD$_0$) with almost sure convergence and a linear convergence rate to solve general standard LP problems. To further improve the efficiency of the (RBCD$_0$) method, we explore the special structure of constraints in the OT problems and leverage the theory of linear systems to propose several approaches for refining the random working set selection and accelerating the vanilla method. Inexact versions of the RBCD methods are also discussed. Our preliminary numerical experiments demonstrate that the accelerated random block coordinate descent (ARBCD) method compares well with other solvers including Sinkhorn's algorithm when seeking solutions with relatively high accuracy, and offers the advantage of saving memory.

[Find arXiv version here](https://arxiv.org/abs/2212.07046)

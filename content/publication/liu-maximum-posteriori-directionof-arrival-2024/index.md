---
title: Maximum A Posteriori Direction-of-Arrival Estimation via Mixed-Integer Semidefinite
  Programming
authors:
- Tianyi Liu
- Frederic Matter
- Alexander Sorg
- Marc E. Pfetsch
- Martin Haardt
- Marius Pesavento
date: '2024-10-01'
publishDate: '2024-12-16T20:55:36.439950Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2311.03501
abstract: In this paper, we consider the maximum a posteriori (MAP) estimation for
  the multiple measurement vectors (MMV) problem with application to direction-of-arrival
  (DOA) estimation, which is classically formulated as a regularized least-squares
  (LS) problem with an $ell_2,0$-norm constraint, and derive an equivalent mixed-integer
  semidefinite program (MISDP) reformulation. The proposed MISDP reformulation can
  be exactly solved by a generic MISDP solver using a semidefinite programming (SDP)
  based branch-and-bound method, which, unlike other nonconvex approaches for the
  MMV problem, such as the greedy methods and sparse Bayesian learning techniques,
  provides a solution with an optimality assessment even with early termination. We
  also present an approximate solution approach based on randomized rounding that
  yields high-quality feasible solutions of the proposed MISDP reformulation at a
  practically affordable computation time for problems of extremely large dimensions.
  Numerical simulations demonstrate the improved error performance of our proposed
  method in comparison to several popular DOA estimation methods. In particular, compared
  to the deterministic maximum likelihood (DML) estimator, which is often used as
  a benchmark, the proposed method applied with the randomized rounding algorithm
  exhibits a superior estimation performance at a significantly reduced running time.
links:
- name: arXiv
  url: https://arxiv.org/abs/2311.03501
---

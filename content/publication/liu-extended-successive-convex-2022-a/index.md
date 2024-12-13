---
title: Extended successive convex approximation for phase retrieval with dictionary
  learning
authors:
- Tianyi Liu
- Andreas M. Tillmann
- Yang Yang
- Yonina C. Eldar
- Marius Pesavento
date: '2022-01-01'
publishDate: '2024-12-09T20:46:43.929959Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Signal Processing*'
abstract: Phase retrieval aims at recovering unknown signals from magnitude measurements
  of linear mixtures. In this paper, we consider the phase retrieval with dictionary
  learning problem, which includes another prior information that the signal admits
  a sparse representation over an unknown dictionary. The task is to jointly estimate
  the dictionary and the sparse representation from magnitude-only measurements. To
  this end, we study two complementary formulations and develop efficient parallel
  algorithms by extending the successive convex approximation framework using a smooth
  majorization. The first algorithm is termed compact-SCAphase and is preferable in
  the case of moderately diverse mixture models with a low number of mixing components.
  It adopts a compact formulation that avoids auxiliary variables. The proposed algorithm
  is highly scalable and has reduced parameter tuning cost. The second algorithm,
  referred to as SCAphase, uses auxiliary variables and is favorable in the case of
  highly diverse mixture models. It also renders simple incorporation of additional
  side constraints. The performance of both methods is evaluated when applied to blind
  channel estimation from subband magnitude measurements in a multi-antenna random
  access network. Simulation results show the efficiency of the proposed techniques
  compared to state-of-the-art methods.
---
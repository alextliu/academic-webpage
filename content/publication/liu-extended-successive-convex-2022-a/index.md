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
publishDate: '2024-12-16T20:55:36.411864Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Signal Processing*'
doi: 10.1109/TSP.2022.3233253
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

featured: true
url_code: "https://github.com/alextliu/PRDL_SmoothingSCA"
url_poster: /PhaseRetreival_ICASSP2021_poster_Liu.pdf

# Summary. An optional shortened abstract.
summary: Developing parallel algorithms for the phase retrieval with dictionary learning problem by extending the successive convex approximation framework using a smooth majorization.

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Magnitude-only measurements in a Multi-antenna Random Access Network'
  focal_point: ""
  preview_only: false
---

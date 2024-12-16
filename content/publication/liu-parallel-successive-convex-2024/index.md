---
title: A parallel successive convex approximation framework with smoothing majorization
  for phase retrieval
authors:
- Tianyi Liu
date: '2024-10-01'
publishDate: '2024-12-16T20:55:36.459768Z'
publication_types:
- thesis
doi: 10.26083/tuprints-00028201
abstract: This dissertation is concerned with the design and analysis of approximation-based
  methods for nonconvex nonsmooth optimization problems. The main idea behind those
  methods is to solve a difficult optimization problem by converting it into a sequence
  of simpler surrogate/approximate problems. In the two widely-used optimization frameworks,
  namely, the majorization-minimization (MM) framework and the successive convex approximation
  (SCA) framework, the approximate function is designed to be a global upper bound,
  called majorizer, of the original objective function and convex, respectively. Generally
  speaking, there are two desiderata of the approximate function, i.e., the tightness
  to the original objective function and the low computational complexity of minimizing
  the approximate function. In particular, we focus on techniques that can be used
  to construct a parallelizable approximate problem so as to take advantage of modern
  multicore computing platforms. The first part of this thesis aims to develop an
  efficient parallelizable algorithmic framework based on approximation techniques
  for a broad class of nonconvex nonsmooth optimization problems. The classic convergence
  result of MM is established on the consistency of directional derivatives in all
  directions between the original objective function and its majorizer at the point
  where the majorizer is constructed. This requirement restricts the majorizer constructed
  at a nondifferentiable point of the original function to be also nonsmooth, which
  hinders its capability of simplifying nonsmooth problems since the minimization
  of the majorizing function, if restricted to be nonsmooth, may still be difficult.
  Therefore, in this thesis, we relax the derivative consistency in the majorization
  step so that a smooth majorizer that can be easily minimized is permitted for a
  wide class of nonsmooth problems.  As a result of this relaxation of derivative
  consistency, the smoothing majorization leads to the convergence to a stationary
  solution in a more relaxed sense than the classic MM. Furthermore, in contrast to
  minimizing the possibly nonconvex majorizing function exactly, the smoothness of
  the majorizing function allows us to employ the idea of SCA, along with available
  separable approximation techniques, to obtain an approximate minimizer of the majorizing
  function efficiently. Thus, we develop a parallelizable inexact MM framework, termed
  smoothing SCA, by combining the smoothing majorization technique and the idea of
  successive convex approximation. In this framework, the construction of the approximate
  problem at each iteration is divided into two steps, namely, the smoothing majorization
  and the convex approximation, so that the two desiderata of the approximate function
  can be treated separately. In addition, both the exact and inexact MM with smoothing
  majorization can be implemented block-coordinatewise to exploit potential separable
  structures of the constraints in the optimization problem. The convergence behaviors
  of the proposed frameworks are analyzed accordingly. In the second part of this
  thesis, as our mainly promoted framework, the smoothing SCA framework is employed
  to address the phase retrieval with dictionary learning problem. Two efficient parallel
  algorithms are developed by applying the smoothing SCA to two complementary nonconvex
  nonsmooth formulations, respectively, which are both based on a least-squares criterion.
  The computational complexities of the proposed algorithms are theoretically analyzed
  and both their error performance and computational time are evaluated by extensive
  simulations in the context of blind channel estimation from subband magnitude measurements
  in multi-antenna random access network, in comparison to the state-of-the-art methods.

featured: true
url_slides: 'SmoothingSCA_slides_Liu_2024-09-26.pdf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'General principle of Successive Convex Approximation'
  focal_point: ""
  preview_only: false
---

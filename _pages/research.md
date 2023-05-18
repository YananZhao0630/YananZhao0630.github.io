---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

* Algorithm Unrolling: Interpretable, Efficient Deep Learning for Signal and Image Processing [[pdf]](https://ieeexplore.ieee.org/document/9363511) (09.2020 -- 06.2022), supervised by [Prof. Vishal Monga (Penn State University, USA)](http://signal.ee.psu.edu/faculty.html), [Yuelong Li (Amazon Lab 126)](https://www.linkedin.com/in/yuelong-li-19ba128b/) and [Prof. Yonina C Eldar (IEEE Fellow, Weizmann Institute of Science, Israel)](https://www.weizmann.ac.il/math/yonina/)
   * Future development and practical deployment of deep neural networks is hindered by their blackbox nature, i.e., lack of interpretability, and by the need for large training sets. To eliminate these issues, deep unrolled networks are proposed by providing a concrete and systematic connection between iterative algorithms and deep neural networks. Deep unrolled networks have attracted enormous attention in computational imaging (e.g., blind image deblurring) and speech processing (e.g., speech enhancement and separation) by means of their efficient, high-performance and yet interpretable network architectures from reasonable size training sets
	<center><img src='/images/P1.png' width="98%" height="98%"/></center>
   * However, convergence properties of the underlying iterative algorithm are lost once layer specific parameters are learned from training data. To address this issue, we propose a deep, convergent unrolled  network for non-blind image deconvolution by developing a new
parametrization scheme.
	<center><img src='/images/P2.png' width="98%" height="98%"/></center>

* Deep Scatterng Network with Fractional Wavelet Transform [[pdf]](https://ieeexplore.ieee.org/document/9495232) (09.2018 -- 09.2020), supervised by Prof. Jun Shi, [Prof. Wei Xiang (La Trobe University, Australia)](https://scholars.latrobe.edu.au/wxiang) and [Prof. Vishal Monga (Penn State University, USA)](http://signal.ee.psu.edu/faculty.html).
  * A central task in machine learning is feature extraction and feature representation is required to be invariant, stable, and informative. To meet these basic requirements, [Prof. Stephane Mallat (IEEE Fellow)](https://www.di.ens.fr/~mallat/mallat.html) proposed [deep scattering networks (DSNs)](https://ieeexplore.ieee.org/document/6522407) by cascading wavelet filters and modulus nonlinearities in each network layer. However, DSNs work well for stationary signals but not for non-stationary ones. 
<figure class="third">
![(a) 2-D Gabor atom]<img src='/images/image120.gif'>
![(b) xxx]<img src='/images/image41.gif'>
![(c) xxx]<img src='/images/image42.gif'>
</figure>

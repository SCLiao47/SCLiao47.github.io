---
title: "A Convex Optimization Approach to Compute Trapping Regions for Lossless Quadratic Systems"
collection: publications
permalink: /publication/202401-TrappingSDP
excerpt: 'This paper focuses developed convex-optimization-based method to verify the boundedness of solutions to Lossless Quadratic ODEs. This convex formulation provides wide connection to literature in modeling, analysis, and design in control and dynamical system using convex methods.'
imagesummary: '/images/Projects/TRSDP_Lorenze_2D.png'
date: 2024-01-09
# venue: 'Under Preparation'
paperurl: 'https://arxiv.org/abs/2401.04787'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
authors: '<b>Shih-Chi Liao</b>, A. Leonid Heide, Maziar S. Hemati, Peter J. Seiler'
---

<!-- \[[Paper on IEEE]()\] /  -->
\[[Paper on arXiv](https://arxiv.org/abs/2401.04787)\] / 
\[[GitHub](https://github.com/SCLiao47/Boundedness_LosslessQuadSys)\] 
<!-- / -->
<!-- \[[Slides](/files/)\] / -->
<!-- \[[Poster](/files/)\] -->

## Abstract
Quadratic systems with lossless quadratic terms arise in many applications, including models of atmosphere and incompressible fluid flows. Such systems have a trapping region if all trajectories eventually converge to and stay within a bounded set. Conditions for the existence and characterization of trapping regions have been established in prior works for boundedness analysis. However, prior solutions have used non-convex optimization methods, resulting in conservative estimates. In this paper, we build on this prior work and provide a convex semidefinite programming condition for the existence of a trapping region. The condition allows precise verification or falsification of the existence of a trapping region. If a trapping region exists, then we provide a second semidefinite program to compute the least conservative trapping region in the form of a ball. Two low-dimensional systems are provided as examples to illustrate the results. A third high-dimensional example is also included to demonstrate that the computation required for the analysis can be scaled to systems of up to $∼O(100)$ states. The proposed method provides a precise and computationally efficient numerical approach for computing trapping regions. We anticipate this work will benefit future studies on modeling and control of lossless quadratic dynamical systems.


![TRSDP_ImageSummary](/images/Projects/TRSDP_Lorenze_2D.png)


## Recommended Citation

```
@misc{liao2024convex,
      title={A Convex Optimization Approach to Compute Trapping Regions for Lossless Quadratic Systems}, 
      author={Shih-Chi Liao and A. Leonid Heide and Maziar S. Hemati and Peter J. Seiler},
      year={2024},
      eprint={2401.04787},
      archivePrefix={arXiv},
      primaryClass={math.OC}
}
```

----

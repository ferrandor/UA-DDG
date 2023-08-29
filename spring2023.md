## May 9, 2023

We had a year-end wrap-up coffee and discussion at Caffe Luce. We will be in touch soon above about our plans for next year!

## April 19, 2023

**Speaker:** [Michael Woodward](https://appliedmath.arizona.edu/person/michael-woodward)

**Title:** Data-Driven Mori-Zwanzig: Theory and Applications to Boundary Layers

**Abstract:** In this talk, we will give a brief overview of a recently developed data-driven Mori-Zwanzig (MZ)
formulation and present applications to boundary layer flows. The MZ formalism provides a mathematically exact procedure for constructing non-Markovian reduced-order models of resolved variables (observables) from high-dimensional dynamical systems, where the effects due to the unresolved dynamics are captured in the memory kernel and orthogonal dynamics. The algorithm used in this work applies Mori’s linear projection operator and an SVD based compression as the selection of the resolved variables (equivalently, a low rank approximation of the two time covariance matrices). We show that this MZ decomposition not only identifies the same spatio-temporal structures found by Dynamic Mode Decomposition (DMD), but it can also be used to extract spatio-temporal structures of the hysteresis effects present in the memory kernels. We perform an analysis of these structures in the context of a laminar-turbulent boundary-layer transition flow over a flared cone at Mach 6, and show the dynamical relevance of the memory kernels. Additionally, by including these memory terms learned in this data-driven MZ approach, we show improvement in the prediction accuracy over DMD at the same level of truncation and at a similar computational cost. Furthermore, an analysis of the spatio-temporal structures of the MZ operators shows identifiable structures associated with the nonlinear generation of the so-called "hot" streaks on the surface of the flared cone, which have previously been observed in experiments and direct numerical simulations. We will conclude with a discussion of ongoing investigations and applications to boundary layer flows, where only sparse sensor measurements are given.  

## March 29, 2023

**Speaker:** [Ari Bormanis](https://appliedmath.arizona.edu/person/ari-bormanis)

**Title:** Encoding Hard Constraints into Physics Informed Neural Networks

**Abstract:** Physics informed neural networks (PINNs) have been a great boon to those hoping to predict the behavior of systems constrained by physical phenomena via machine learning. PINNs usually function by embedding soft constraints into their cost function used for learning. Unfortunately, due to the soft nature of the constraints, this can result in PINNs making predictions that do not obey known physical laws. In particular, we focus on PINNs used for predicting magnetic fields and fluid velocity fields. These two cases are similar in that both magnetic fields and fluid velocity fields (for incompressible fluids) obey the zero divergence condition. We explain how the zero divergence condition can be embedded into the structure of a PINN as a hard constraint and the beneficial results of this. 

**Papers:** The ideas in this talk come from the papers "Physics-constrained 3D Convolutional Neural Networks for Electrodynamics" by Alexander Scheinker and Reeju Pokharel (link: https://arxiv.org/abs/2301.13715), and "Embedding Hard Physical Constraints in Convolutional Neural Networks for 3D Turbulence" by Arvind T. Mohan, Nicholas Lubbers, Daniel Livescu, and our very own Michael Chertkov (link: https://openreview.net/forum?id=IaXBtMNFaa).

## March 15, 2023

**Speakers:** Alexa Aucoin and Robert Ferrando

Alexa Aucoin will give a review of Neural ODE as well as a high-level discussion on Graph Neural Networks (GNN) in the first half of the meeting. In the second half of the meeting, Robert Ferrando will lead a software demo of [Neuromancer](https://github.com/pnnl/neuromancer), a Pytorch-based package for solving parametric constrained optimization problems.

## February 15, 2023

**Journal Club**

**Speaker**: Robert Ferrando

Koch et al., "Structural Inference of Networked Dynamical Systems with Universal Differential Equations", 2022. 
Download the paper [here](https://aps.arxiv.org/abs/2207.04962) or [here](https://aip.scitation.org/doi/full/10.1063/5.0109093).
Notes/slides will be provided after the meeting.

Check this blog post by Chris Rackauckas out: [Direct Automatic Differentiation of (Differential Equation) Solvers vs Analytical Adjoints: Which is Better?](https://www.stochasticlifestyle.com/direct-automatic-differentiation-of-solvers-vs-analytical-adjoints-which-is-better/).

## February 1, 2023

**Question Blitz**

The Data and Dynamics Group will hold its next meeting on Wed. 2/1 @ 1pm in MATH 501. For this meeting we would like to hold an informal "Question Blitz" where everyone is invited to participate. This is an opportunity for everyone to share some brief background about the topic(s) they are interested in, as well as what questions they would like to answer but may not know how to address. This is also a good space to present some "half baked" ideas to an audience. If time permits, we will have a roundtable discussion following the blitz about any common themes that we may want to discuss further this term. 


If you think you might participate, please [sign-up](https://docs.google.com/spreadsheets/d/1krjwyw24YpVYxZ6xsm4j1boaqeihLteOJ_w6ShHNoIM/edit?pli=1#gid=0) by next Tuesday 1/31 so we can get a general sense of how many talks we will have. Also see below for some general guidelines.


We hope to see and hear from you all! 


**Question Blitz Guidelines:**

* Time - Strict 4 mins (3 mins for talk, 1 for questions)
* Topics - Can be broad or narrow in scope, try to think about topics related to the general themes of data & dynamics.
* Visual Aids - Optional. Max of 2 slides, if any. Chalkboard talks are also welcome! (Please bring your own device if you plan to present slides.) 


## January 18, 2023

**Speaker**: [Jared McBride](https://appliedmath.arizona.edu/person/jared-mcbride)

**Title**: Spectral Estimation and Iterated Whitening

**Abstract**: The power spectrum of a stationary stochastic process characterizes the amount of “energy” in different frequencies, and power spectra are a fundamental tool in data analysis, signal processing, and linear prediction and control. Standard methods for estimating power spectra from data can be highly inaccurate when the dynamic range of the spectrum is large.  In this talk, I present a novel method for accurately estimating the power spectra of signals from data. The method, based on an iterated “whitening” procedure, is designed to work well for spectra with high dynamic range.  I compare the iterated whitening method with two standard methods, and illustrate its use on a prototypical model of spatiotemporal chaos.

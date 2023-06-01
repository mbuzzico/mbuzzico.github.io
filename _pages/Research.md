---
layout: single
title: "Research"
permalink: /Research/
header:
    overlay_image: /assets/images/Research.png
    #caption: "*Eddies within the Antarctic Circumpolar Current in the [NeverWorld2](https://doi.org/10.5194/gmd-15-6567-2022) model.*"
author_profile: true
classes: wide

---
{: style="text-align: justify;"}
Below, I summarize some of the important achievements that characterize my scientific background.
{: style="text-align: justify;"}

## Analysis of Ocean circulation data.

<div style="width:60%;  padding-left: 10px; float:right">
    {% include figure image_path="/assets/images/AnalysisofOceancirculationdata.png" %}
</div>
I have contributed to pioneer the **Ocean circulation analysis** using the **Coarse-Graining method on the sphere**. In recent papers we have measured the global energy spectrum of the general oceanic circulation [1,2], see Fig. 1. That has contributed to highlight clearly and quantitatively the richness of the multiscale Ocean physics. From the presence of a peak of energy at scales 9000 km due to the Antarctic Circumpolar Current, to the existence of power-law scaling behaviour E(k)∼k^(-1) at the gyre-scales >1000 km that opens new theoretical questions concerned with the energy cascading process that is generating such power-law scaling. We have also observed a drift in the seasonal cycle of larger scales, which is delayed by roughly 40 days every octave of scales, such that 100km peaks in spring and 1000km peaks in late summer. **I am confident that Coarse-Graining will also lead to new observations, as in particular it will allow to measure the Ocean energy fluxes from large to the smaller scales that new satellite missions aims to resolve.**


## Data Assimilation problems. 

<div style="width:60%;  padding-left: 10px; float:right">
    {% include figure image_path="/assets/images/DataAssimilationproblems.png" %}
</div>
I have helped pioneer the application of machine learning approaches such as **GANs** based convolutional networks (CN) to the reconstruction of missing data in turbulence [3], distinguishing four possible different questions, see Fig. 2. Following a reverse engineering approach, I have investigated the possibility of ranking the input flow properties in terms of their qualitative and quantitative importance to obtain a better set of reconstructed fields. I have investigated the capabilities of **physics-informed neural networks** in solving inverse problems such as the reconstruction of the turbulent Rayleigh-Bénard velocity field using only temperature measurements, and performed a quantitative analysis of the quality of the reconstructions [4]. In another recent work, I discussed the possibility of using CN to classify different turbulent environments from partial observations, a key problem in many applied fields, from engineering to Earth observation [5]. I have contributed to the study of **nudging** with very promising results for physics and flow reconstructions [3,6]. I have recently authored a Perspective Review paper in Europhysics Letters, with the aim of reviewing the main ML algorithms that play an important role in current developments, the problem of reconstructing missing data, uncovering potential avenues, and discussing the open challenges for applications to fluid mechanics. [7]. 

## Machine Learning for Lagrangian problems. 
{: style="text-align: justify;"}
I contributed to pioneer applications of **Reinforcement  Learning** to particles control in turbulent multi-scale flows, for **optimal navigation** of **self-propelling particles**. We have used a theoretical and numerical approach to find results concerning the problem to find the path that minimizes the time to navigate between two given points in a complex fluid under realistic navigation constraints [8,9]. Using an approach that can be generalized to realistic setups, for example, navigation under imperfect knowledge of the environmental state, we have shown that the Data-Driven RL algorithms are able to find **quasi-optimal solutions** robust to the **chaotic nature** of the evolving system. 
{: style="text-align: justify;"}

## Direct/Inverse Turbulent Energy Cascades. 

<div style="width:60%;  padding-left: 10px; float:right">
    {% include figure image_path="/assets/images/DirectInverseTurbulentEnergycascades.png" %}
</div>
I have implemented novel numerical approaches based on coarse-graining methods to study transitions in the turbulent transfer from purely 3d [10] flows to **turbulence with rotation** [11], also in **thick layers or tall boxes** with interest in studying the **energy transfer phase transitions** type in rotating turbulence [12]. The discussions on these topics with Prof. Auie have helped to lay the foundations for the new born coarse-graining approach on the sphere, recently applied to the study of ocean dynamics.

## Lattice Boltzmann Methods. 
{: style="text-align: justify;"}
I have contributed to implement novel developments of Lattice Boltzmann modelling, **Entropic LBM (ELBM)**, with applications on high turbulent 2d and 3d flows. From the macroscopic formulation of the ELBM, we have derived a new hydrodynamical closure for **Large-Eddy Simulations** able to model the **backscatter** events **of energy** transferred from the subgrid to the resolved scales (**M. Buzzicotti**, G. Tauzin “Inertial range statistics of the entropic lattice Boltzmann method in three-dimensional turbulence. Physical Review E 2021, see the publications list on my scholar). 
{: style="text-align: justify;"}

## Intermittency and extreme-events. 
{: style="text-align: justify;"}
I contributed to develop the application of **Multifractal** and **Large Deviations** theory to small-scale turbulence both in Eulerian and Lagrangian domains fully developed turbulent flows on 3d domain [13] and on sets with different Fractal dimensions [14]. My results supported the effectiveness of Multifractal theory to give a **phenomenological** explanation of **intermittency** in turbulence also when bridging both the Eulerian and Lagrangian descriptions. 
{: style="text-align: justify;"}

## Burgers' equation.
<div style="width:60%;  padding-left: 10px; float:right">
    {% include figure image_path="/assets/images/Burgersequation.png" %}
</div>
In order to gain some theoretical insight of the connection between small-scale structures and intermittency in 3d turbulence, I also studied the **robustness of singular solutions** in non-linear 1D PDEs upon **reducing the number of degrees of freedom** based on a **Galerkin** projection approach (with L. Biferale, U. Frisch, S.S. Ray. Physical Review E 2016) [15]. Focusing on the Burgers’ equation I studied the connection between shock-like solutions in physical space and **synchronization of Fourier-space phase dynamics** (see **M. Buzzicotti**, B.P. Murray, L. Biferale, M.D. Bustamante European Physical Journal E 2016 on my scholar page), see Fig. 4 for a graphical illustration. Furthermore, I examined the role of the **non-linear multiscale coupling** in fluid dynamics, which is a key question for all modelling approaches of turbulence.

{: style="text-align: justify;"}

--------------------------

{: style="text-align: justify;"}
**15 papers (the ones more relevant for the application not the most cited).** TC: time cited (Google Scholar). 
{: style="text-align: justify;"}

**[1]** B.A. Storer, **M. Buzzicotti**, H. Khatri, S.M. Griffies, H. Aluie. Global energy spectrum of the general oceanic circulation. Nature communications 13 (1), 1-9, (2022). **TC 5.**
{: style="text-align: justify;"}
**[2] M. Buzzicotti**, B.A. Storer, S.M. Griffies, H. Aluie. Spatio-temporal coarse-graining decomposition of the global ocean geostrophic kinetic energy. arXiv preprint arXiv:2106.04157, (2021). **TC 7.**
{: style="text-align: justify;"}
**[3] M. Buzzicotti**, F. Bonaccorso, P. Clark Di Leoni, L. Biferale. Reconstruction of turbulent data with deep generative models for semantic inpainting from TURB-Rot database. Physical Review Fluids 6 (5), 050503, (2021). **TC 24.**
{: style="text-align: justify;"}
**[4]** P. Clark Di Leoni, L. Agasthya, **M. Buzzicotti**, and L. Biferale. Reconstructing Rayleigh-Benard flows out of temperature-only measurements using Physics-Informed Neural Networks. The European Physical Journal E 45.12:102, (2022). **TC 1.**
{: style="text-align: justify;"}
**[5] M. Buzzicotti**, and F. Bonaccorso. Inferring turbulent environments via machine learning. European Physical Journal E 46(3),16 (2023). **TC 1.**
{: style="text-align: justify;"}
**[6] M. Buzzicotti**, P. Clark Di Leoni. Synchronizing subgrid scale models of turbulence to data. Physics of Fluids 32 (12), 125116, (2021). **TC 17.**
{: style="text-align: justify;"}
**[7] M. Buzzicotti.** Data reconstruction for complex flows using AI: recent progress, obstacles, and perspectives. Europhysics Letters, (2023). **TC 0.**
{: style="text-align: justify;"}
**[8]** L. Biferale, F. Bonaccorso, **M. Buzzicotti**, P. Clark Di Leoni and K. Gustavsson. Zermelo’s problem: Optimal point-to-point navigation in 2D turbulent ﬂows using Reinforcement Learning. Chaos: An Interdisciplinary Journal of Nonlinear Science 29 (10), 103138, (2019). **TC 65.**
{: style="text-align: justify;"}
**[9] M. Buzzicotti**, L. Biferale, F. Bonaccorso, P. Clark di Leoni & K. Gustavsson. Optimal control of point-to-point navigation in turbulent time dependent flows using Reinforcement Learning. In AIxIA 2020–Advances in Artificial Intelligence: XIXth International Conference of the Italian Association for Artificial Intelligence, Revised Selected Papers (pp. 223-234). Cham: Springer International Publishing, (2020). **TC 9.**
{: style="text-align: justify;"}
**[10] M. Buzzicotti**, M. Linkmann, H. Aluie, L. Biferale, J. Brasseur, C. Meneveau. Effect of filter type on the statistics of energy transfer between resolved and subfilter scales from a-priori analysis of direct numerical simulations of isotropic turbulence. Journal of Turbulence 19 (2), 167-197, (2018). **TC 50.**
**[11] M. Buzzicotti**, H. Aluie, L. Biferale, M. Linkmann. Energy transfer in turbulence under rotation. Physical Review Fluids 3 (3), 034802, (2018). **TC 49.**
{: style="text-align: justify;"}
**[12]** PC Di Leoni, A. Alexakis, L. Biferale & **M. Buzzicotti**. Phase transitions and flux-loop metastable states in rotating turbulence. Physical Review Fluids 5 (10), (2020). TC 12.
{: style="text-align: justify;"}
**[13]** L. Biferale, F. Bonaccorso, **M. Buzzicotti**, K. P. Iyer.  Self-similar subgrid-scale models for inertial range turbulence and accurate measurements of intermittency.  Physical Review Letters 123 (1), 014503, (2019). **TC 14.**
{: style="text-align: justify;"}
**[14] M. Buzzicotti**, A. Bhatnagar, L. Biferale, A.S. Lanotte, S.S. Ray. Lagrangian statistics for Navier–Stokes turbulence under Fourier-mode reduction: fractal and homogeneous decimations. New Journal of Physics 18 (11), 113047, (2016). **TC 26.**
{: style="text-align: justify;"}
**[15] M. Buzzicotti**, L. Biferale, U. Frisch, S.S. Ray Intermittency in fractal Fourier hydrodynamics: Lessons from the Burgers equation. Physical Review E 93 (3), 033109, (2016). **TC 25.**
{: style="text-align: justify;"}

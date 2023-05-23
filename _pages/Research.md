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
My background and training are in **Theoretical Physics, Statistical Mechanics, High Performance Computing, Big Data,** and **Physics of the Atmosphere and Meteorology**. I have always enjoyed approaching geophysical questions with both a theoretical and a numerical point of view. Since the beginning of my research career, I worked on **Dynamical System** and **Turbulence** (both phenomenology and numerical simulations, with/without particles, in different setups, isotropic, anisotropic, wall-bounded, rotating/stratified), using **Pseudo-Spectral, Finite Difference** codes, **Lattice Boltzmann** and **Data-Driven numerical Methods**, where I have been the person in charge in the group for the development of High-Performance codes to be executed on some of the European largest HPC facilities. My activity ranges from the development of non-linear, out of equilibrium models for small-scale closure of high Reynolds flows to the **control Lagrangian Turbulent problems** [10]. From the applied point of view, I have worked on questions such as **optimal navigation** in complex environments [6]. Today I am mainly active on the side of **Data Reconstruction** and **Physics-Inferring** problems, where I have worked on idealized/complex setups as high Reynolds rotating turbulent flows to reconstruct missing data from partial measurements [3,4,5]. I have also recently initiated a new important field of research on **Geophysical Data Analysis** with the goal to disentangle the role of the multiscale physics mechanisms at play in the Ocean, resulted recently in the publication of the kinetic global energy spectrum of the general Ocean circulation [1,2]. 
{: style="text-align: justify;"}

Below, I summarize some of the important previous achievements that characterize my scientific background.
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



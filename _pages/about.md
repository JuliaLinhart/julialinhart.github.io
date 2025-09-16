---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello!

I am a Postdoctoral Researcher at NYU Center for Data Science, working with [Julia Kempe](https://cims.nyu.edu/~kempe/) (NYU), [Shirley Ho](https://www.shirleyho.space/) (NYU - Flatiron Institute), and [Uroš Seljak](https://physics.berkeley.edu/people/faculty/uros-seljak) (UC Berkeley). 
I completed my PhD at Inria ([MIND Team](https://team.inria.fr/mind/)), Université Paris-Saclay under the supervision of [Alexandre Gramfort](https://alexandre.gramfort.net/) (Meta) and [Pedro L. C. Rodrigues](https://plcrodrigues.github.io/) (Inria, Grenoble). 

My research focuses on **probabilistic machine learning**, **simulation-based inference** and **generative modeling**, with applications in neuroscience, cosmology, and beyond. 

I am most excited about how AI can transform the way we do science! 

## News

- Sept 2025: Started postdoc at NYU Center for Data Science.

- August 2025: New tutorial paper on Simulation-Based Inference out with Max Planck collaborators. [link to paper](https://arxiv.org/abs/2508.12939)

- Dec 2024: Successfully defended my PhD at Inria Saclay. [link to video](https://www.youtube.com/watch?v=he1HbmhwGCw)

## Research

<!-- My research combines probabilistic machine learning and scientific applications, with a special focus on simulation-based inference and generative modeling.  -->
The primary focus of my research has been on the use of **deep generative models** (normalizing flows and diffusion models) in **simulation-based inference** (SBI). The goal is to develop methods for more accuracte, efficient and reliabile inference on complex biophysical simulators - in neuroscience, astrophysics and beyond. Ultimately, my research seeks to build greater trust in AI as a tool for scientific discovery. 

### Current Directions
Scaling simulation-based inference for cosmology, while deepening my expertise in generative models and theoretical machine learning. This work is in close collaboration with colleagues at [NYU Center for Data Science](https://cds.nyu.edu/), the [Flatiron Institute](https://www.simonsfoundation.org/flatiron/) / [Polymathic AI](https://polymathic-ai.org/), and [Berkeley Center for Cosmological Physics](https://bccp.berkeley.edu/). **Stay tuned…**

### Main PhD projects

- Development of **new validation diagnostics for conditional deep generative models** [1, 2], with an integration to the official [`sbi`](https://github.com/sbi-dev/sbi) python package from the [MACKELAB](https://www.mackelab.org/).
<!-- - A benchmark initiative for SBI algorithms in collaboration with the [MACKELAB](https://www.mackelab.org/) and Thomas Moreau. It combins the `sbibm` and `benchopt` packages, with the goal of standardized and maintained SBI methods, and an easy to use benchmark framework with open source code and reproducible results.-->
- Exploration of **novel posterior sampling algorithms using deep generative models**, for example based on diffusion models when one wishes to condition on multiple observations to get more precise parameter estimations [3]. This is collaborative work with [Sylvain Le Corff](https://sylvainlc.github.io/) (LPSM - Sorbonne Université) and [Gabriel V. Cardoso](https://gabrielvc.github.io/) (CMAP - École Polytechnique). 
<!-- Ongoing work with Marylou Gabrié and Louis Grenioux explores the use and combination of energy based models (EBMs) and normalizing flows for the sampling of highly structured posterior distributions. -->
- Application of SBI to neuroscience time series (EEG) data [4].

### Other 
Before my PhD, I had the chance to work more closely on ML applications in *Medical Imaging* at two different start-ups:
- [Covera Health](https://www.coverahealth.com/) (New York) - **uncertainty quantification of deep classification models** on MRIs - and 
- [Owkin](https://www.owkin.com/) (Paris) - **development and calibration of deep survival models** for breast cancer prognosis on histology images.

## Open Source 
I am an active contributor to the [`sbi`](https://github.com/sbi-dev/sbi) Python toolbox.

## CV

Here is [my CV](/files/Research_CV_Linhart.pdf). For more details, feel free to contact me at julia.linhart@nyu.edu :)




<!-- ## Funding

My PhD project is part of the [ED STIC](https://www.universite-paris-saclay.fr/ecoles-doctorales/sciences-et-technologies-de-linformation-et-de-la-communication-stic) doctoral school at Université Paris-Saclay. As the first-placed candidate of my year, I am recipient of the *Pierre-Aguilar Scholarship* of the [Capital Fund Management (CFM)](https://www.fondation-cfm.org/). -->

## References

[1] Julia Linhart, Alexandre Gramfort and Pedro L. C. Rodrigues, [*Validation Diagnostics for SBI algorithms based on Normalizing Flows*](https://arxiv.org/abs/2211.09602), ML4PS Workshop, NeurIPS 2022.\
[2] Julia Linhart, Alexandre Gramfort and Pedro L. C. Rodrigues, [*L-C2ST: Local Diagnostics for Posterior Approximations in Simulation-Based Inference*](https://arxiv.org/abs/2306.03580), NeurIPS 2023.\
[3] Julia Linhart, Gabriel V. Cardoso, Alexandre Gramfort, Sylvain Le Corff and Pedro L. C. Rodrigues, [*Diffusion posterior sampling for simulation-based inference in tall data settings*](https://arxiv.org/abs/2404.07593), 2024.\
[4] Julia Linhart, Pedro L. C. Rodrigues, Thomas Moreau, Gilles Louppe, Alexandre Gramfort,
[*Neural Posterior Estimation of hierarchical models in neuroscience*](https://hal.science/hal-03858828/file/Gretsi_2022_HNPE.pdf), Colloque GRETSI 2022.
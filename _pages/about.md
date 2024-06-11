---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello!

I am a PhD Student within the [MIND team](https://team.inria.fr/mind/) (former [Parietal](https://team.inria.fr/parietal/)) at INRIA Saclay, working under the supervision of [Alexandre Gramfort](https://alexandre.gramfort.net/) and [Pedro L. C. Rodrigues](https://plcrodrigues.github.io/) on simulation-based inference (SBI) and generative modelling.

The primary focus of my research has been on the use of **deep generative models** (in particular normalizing flows and diffusion models) to address **likelihood-free Bayesian inference** (a.k.a. LFI or [SBI](https://arxiv.org/abs/1911.01429)) tasks and their **validation** in terms of accuracy, efficiency and reliability. This work is motivated by the goal of efficiently inverting complex simulators from computational neuroscience and more generally to lift the remaining lack of trust for deep generative models to address important questions in experimental sciences. My main projects and collaborations are detailed below.

Before my PhD, I have also had the chance to work more closely on applications in **Machine Learning for healthcare** at two different start-ups, [Covera Health](https://www.coverahealth.com/) in New York (uncertainty quantification of Deep Learning models on MRIs) and [Owkin](https://www.owkin.com/) in Paris (development of Deep Learning models for breast cancer survival analysis on histology images and their calibration).

I am particularly interested in expanding my expertise on generative models and gaining a more profound understanding of their workings, my motivation being a mix of pure curiosity and the goal of applying them to aid experimental sciences accross various biophysical fields.

Here is [my CV](/files/Resume_Linhart.pdf). For more details, feel free to contact me at julia.linhart@inria.fr .

## Main PhD projects and collaborations

- Development of **new validation diagnostics for conditional deep generative models** [1, 2], with an integration to the official [`sbi`](https://github.com/sbi-dev/sbi) python package from the [MACKELAB](https://www.mackelab.org/).
<!-- - A benchmark initiative for SBI algorithms in collaboration with the [MACKELAB](https://www.mackelab.org/) and Thomas Moreau. It combins the `sbibm` and `benchopt` packages, with the goal of standardized and maintained SBI methods, and an easy to use benchmark framework with open source code and reproducible results.-->
- Exploration of **novel posterior sampling algorithms using deep generative models**, for example based on diffusion models when one wishes to condition on multiple observations to get more precise parameter estimations [3]. This is collaborative work with [Sylvain Le Corff](https://sylvainlc.github.io/) and [Gabriel V. Cardoso](https://gabrielvc.github.io/). 
<!-- Ongoing work with Marylou Gabrié and Louis Grenioux explores the use and combination of energy based models (EBMs) and normalizing flows for the sampling of highly structured posterior distributions. -->


## Funding

My PhD project is part of the [ED STIC](https://www.universite-paris-saclay.fr/ecoles-doctorales/sciences-et-technologies-de-linformation-et-de-la-communication-stic) doctoral school at Université Paris-Saclay. As the first-placed candidate of my year, I am recipient of the *Pierre-Aguilar Scholarship* of the [Capital Fund Management (CFM)](https://www.fondation-cfm.org/).

## References

[1] Julia Linhart, Alexandre Gramfort and Pedro L. C. Rodrigues, [*Validation Diagnostics for SBI algorithms based on Normalizing Flows*](https://arxiv.org/abs/2211.09602), ML4PS Workshop, NeurIPS 2022.\
[2] Julia Linhart, Alexandre Gramfort and Pedro L. C. Rodrigues, [*L-C2ST: Local Diagnostics for Posterior Approximations in Simulation-Based Inference*](https://arxiv.org/abs/2306.03580), NeurIPS 2023.\
[3] Julia Linhart, Gabriel V. Cardoso, Alexandre Gramfort, Sylvain Le Corff and Pedro L. C. Rodrigues, [*Diffusion posterior sampling for simulation-based inference in tall data settings*](https://arxiv.org/abs/2404.07593), Preprint, 2024.

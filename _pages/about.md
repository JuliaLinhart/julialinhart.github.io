---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello!

I am a PhD Student within the [MIND team](https://team.inria.fr/mind/) (former [Parietal](https://team.inria.fr/parietal/)) at INRIA Saclay, working under the supervision of [Alexandre Gramfort](https://alexandre.gramfort.net/) and [Pedro L. C. Rodrigues](https://plcrodrigues.github.io/) on [simulation-based inference (SBI)](https://arxiv.org/abs/1911.01429) and generative modelling.

The primary focus of my research has been on the use of **deep generative models** (e.g. normalizing flows, diffusion models, etc.) to address **likelihood-free Bayesian inference** (a.k.a. [SBI](https://arxiv.org/abs/1911.01429)) tasks and their **validation** in terms of accuracy, efficiency and reliability. This work is motivated by the goal of efficiently inverting complex simulators from computational neuroscience and more generally to lift the remaining lack of trust for deep generative models to address important questions in experimental sciences. My main projects and collaborations are detailed below.

Before my PhD, I have also had the chance to work more closely on applications in **Machine Learning for healthcare** at two different start-ups, [Covera Health](https://www.coverahealth.com/) in New York (uncertainty quantification of Deep Learning models on MRIs) and [Owkin](https://www.owkin.com/) in Paris (development of Deep Learning models for breast cancer survival analysis on histology images and their calibration).

I am particularly interested in expanding my expertise on generative models and gaining a more profound understanding of their workings, my motivation being a mix of pure curiosity and the goal of applying them to aid experimental sciences accross various biophysical fields.

Here is [my CV](/files/Resume_Linhart.pdf). For more details, feel free to contact me at julia.linhart@inria.fr .

## Main PhD projects and collaborations

- The development of new **validation diagnostics for conditional deep generative models** [[1]](https://arxiv.org/abs/2211.09602) [[2]](https://arxiv.org/abs/2306.03580), with an integration to the official [`sbi`](https://github.com/sbi-dev/sbi) python package. This work was done in collaboration with [Alexandre Gramfort](https://alexandre.gramfort.net/), [Pedro L. C. Rodrigues](https://plcrodrigues.github.io/), [Gilles Louppe](https://glouppe.github.io/) and the [MACKELAB](https://www.mackelab.org/).
- The exploration of novel **posterior sampling algorithms using deep generative models**, for example based on diffusion models when one wishes to condition on multiple observations to get more precise parameter estimations [[3]](https://arxiv.org/abs/2404.07593). This is collaborative work with [Sylvain Le Corff](https://sylvainlc.github.io/) and [Gabriel V. Cardoso](https://gabrielvc.github.io/).


## Funding

My PhD project is part of the doctoral school [ED STIC](https://www.universite-paris-saclay.fr/ecoles-doctorales/sciences-et-technologies-de-linformation-et-de-la-communication-stic) at Université Paris-Saclay. As first-placed candidate, I am recipient of the *Pierre-Aguilar Scholarship* of the [Capital Fund Management (CFM)](https://www.fondation-cfm.org/).

## References

[[1]](https://arxiv.org/abs/2211.09602) *Validation Diagnostics for SBI algorithms based on Normalizing Flows*, ML4PS Workshop, NeurIPS 2022.\
[[2]](https://arxiv.org/abs/2306.03580) *L-C2ST: Local Diagnostics for Posterior Approximations in Simulation-Based Inference*, NeurIPS 2023.\
[[3]](https://arxiv.org/abs/2404.07593) *Diffusion posterior sampling for simulation-based inference in tall data settings*, in proceedings, 2024.

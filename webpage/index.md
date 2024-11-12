---
layout: home
---

# Tutorial on Differentiable Probabilistic Programming for Agent-Based Models [ICAIF 2024]

Welcome to the tutorial on differentiable agent-based models!

# Description

This tutorial will introduce a new paradigm for agent-based models (ABMs) that leverages automatic differentiation (AD) to efficiently compute simulator gradients. In particular, this tutorial will provide:

1. An overview of vanilla AD and AD methods to differentiate through discrete stochastic programs.
2. A walkthrough on how to build a differentiable economic ABM.
3. State-of-the-art methods for calibrating differentiable ABMs.

# Target audience

The tutorial is aimed at members of the ICAIF community who are interested in the deployment, calibration and analysis of large-scale agent-based models. No previous experience with automatic differentiation will be required to understand the tutorial material. 

# Outline and Schedule

Date: Friday 15th of November 2024

| Time | Session | Speaker |
| --- | --- | --- |
| 08:00 - 08:40 | Automatic Differentiation for Agent-Based Models| Nicholas Bishop|
| 08:40 - 08:50 | Break| |
| 08:50 - 09:45 | Gradient-assisted calibration techniques for ABMs| Joel Dyer|

# Materials

We have created a set of Jupyter notebooks which provide a practical walkthrough of the tutorial material. You can access the Google colab and nbviewer versions of each notebook via the links below. 

1. Automatic Differentiation: [[Colab]](https://colab.research.google.com/github/LargeAgentCollider/icaif_tutorial/blob/main/notebooks/01-automatic-differentiation.ipynb) [[nbviewer]](https://nbviewer.org/github/LargeAgentCollider/icaif_tutorial/blob/main/notebooks/01-automatic-differentiation.ipynb)
2. Differentiating Randomness: [[Colab]](https://colab.research.google.com/github/LargeAgentCollider/icaif_tutorial/blob/main/notebooks/02-differentiating-randomness.ipynb)[[nbviewer]](https://nbviewer.org/github/LargeAgentCollider/icaif_tutorial/blob/main/notebooks/02-differentiating-randomness.ipynb)
3. Differentiable ABMs: [[Colab]](https://colab.research.google.com/github/LargeAgentCollider/icaif_tutorial/blob/main/notebooks/03-differentiable-abm.ipynb)[[nbviewer]](https://nbviewer.org/github/LargeAgentCollider/icaif_tutorial/blob/main/notebooks/03-differentiable-abm.ipynb)
4. Variational Inference: [[Colab]](https://colab.research.google.com/github/LargeAgentCollider/icaif_tutorial/blob/main/notebooks/04-variational-inference.ipynb)[[nbviewer]](https://nbviewer.org/github/LargeAgentCollider/icaif_tutorial/blob/main/notebooks/04-variational-inference.ipynb)

Presentation slides, which supplement the notebooks above, are available [here]({{ site.baseurl }}/icaif_slides.pdf). 

# Presenters

[Joel Dyer](https://joelnmdyer.github.io) is a senior postdoctoral researcher at the University of Oxford’s Department of Computer Science and a Senior Research Fellow at the Oxford Institute for New Economic Thinking. 

[Nick Bishop](http://www.nickbishop.net) is a postdoctoral researcher at the University of Oxford, working within the Department of Computer Science on problems at the intersection of machine learning and agent-based modelling.

[Ani Calinescu]() is an Associate Professor at the University of Oxford's Department of Computer Science, a Senior Research Fellow at the Oxford Institute for New Economic Thinking, and a Co-Investigator on a UKRI-funded project on Robust Large-Scale Agent-Based Modelling, and a Co-PI or Co-Investigator on several JPMC Faculty Research Awards.

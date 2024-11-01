# Tutorial on Differentiable Probabilistic Programming for Agent-Based Models [ICAIF 2024]

Welcome to the tutorial on differentiable agent-based models!

# Description

This tutorial will introduce a new paradigm for agent-based models (ABMs) that leverages automatic differentiation (AD) to efficiently compute the simulator's gradients. The tutorial will cover:

1. An overview of vanilla AD and AD methods to differentiate through discrete stochastic programs.
2. Examples of differentiable ABMs with millions of agents used to study disease spread across multiple countries.
3. State-of-the-art methods for calibrating differentiable ABMs.

# Target audience

The tutorial is aimed at the thos in the ICAIF community who share an interest on agent-based modelling and how to make it deployable to the real world at scale. 

# Outline and Schedule

Date: Friday 15th of November 2024

| Time | Session | Speaker |
| --- | --- | --- |
| 08:00 - 08:40 | Automatic Differentiation for Agent-Based Models| Nicholas Bishop|
| 08:40 - 08:50 | Break| |
| 08:50 - 09:45 | Gradient-assisted calibration techniques for ABMs| Joel Dyer|

# Materials

You can access the slides [here](webpage/AAMAS_Tutorial.pdf)

We also provided accompanying Jupyter notebooks for practical demonstrations of the presented methodologies. The notebooks can be found in the `tutorials` directory. You can access the google colab and markdown-rendered versions here:

1. Automatic Differentiation: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/01-automatic-differentiation.ipynb) [[Markdown]](01-automatic-differentiation)
2. Differentiating Randomness: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/02-differentiating-randomness.ipynb)[[Markdown]](02-differentiating-randomness)
3. Differentiable ABMs: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/03-differentiable-abm.ipynb)[[Markdown]](03-differentiable-abm)
4. Variational Inference: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/04-variational-inference.ipynb)[[Markdown]](04-variational-inference)

# Presenters

[Joel Dyer](https://joelnmdyer.github.io) is a senior postdoctoral researcher at the University of Oxford’s Department of Computer Science and a Senior Research Fellow at the Oxford Institute for New Economic Thinking. 

[Nick Bishop]() is a postdoctoral researcher at the University of Oxford's Department of Computer Science.

[Ani Calinescu]() is an Associate Professor at the University of Oxford's Department of Computer Science, a Senior Research Fellow at the Oxford Institute for New Economic Thinking, and a Co-Investigator on a UKRI-funded project on Robust Large-Scale Agent-Based Modelling, and a Co-PI or Co-Investigator on several JPMC Faculty Research Awards.

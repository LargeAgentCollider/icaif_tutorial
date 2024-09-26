# Tutorial on Differentiable Probabilistic Programming for Agent-Based Models [ICAIF 2024]

Welcome to the tutorial on differentiable agent-based models!

# Description

This tutorial will introduce a new paradigm for agent-based models (ABMs) that leverages automatic differentiation (AD) to efficiently compute the simulator's gradients. The tutorial will cover:

1. An overview of vanilla AD and AD methods to differentiate through discrete stochastic programs.
2. Examples of differentiable ABMs with millions of agents used to study disease spread across multiple countries.
3. State-of-the-art methods for simulating, calibrating, and analyzing differentiable ABMs.
4. Integration of differentiable ABMs into probabilistic programming pipelines.
5. Applications of AD for generating synthetic populations.


# Target audience

The tutorial is aimed at the thos in the ICAIF community who share an interest on agent-based modelling and how to make it deployable to the real world at scale. 

# Outline and Schedule

Date: Friday 15th of November 2024

| Time | Session | Speaker |
| --- | --- | --- |
| 08:00 - 08:30 | Automatic Differentiation for Agent-Based Models| Arnau Quera-Bofarull|
| 08:30 - 09:00 | Gradient-assisted calibration techniques for ABMs| Joel Dyer|
| 09:00 - 09:30 | Differentiable synthetic population generation | Nick Bishop and Imran Mahmood |
| 09:30 - 09:45 | Closing remarks and future work | Arnau Quera-Bofarull |

# Materials

You can access the slides [here](webpage/AAMAS_Tutorial.pdf)

We also provided accompanying Jupyter notebooks for practical demonstrations of the presented methodologies. The notebooks can be found in the `tutorials` directory. You can access the google colab and markdown-rendered versions here:

1. Automatic Differentiation: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/01-automatic-differentiation.ipynb) [[Markdown]](01-automatic-differentiation)

2. Differentiating Randomness: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/02-differentiating-randomness.ipynb)[[Markdown]](02-differentiating-randomness)
3. Differentiable ABMs: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/03-differentiable-abm.ipynb)[[Markdown]](03-differentiable-abm)
4. Variational Inference: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/04-variational-inference.ipynb)[[Markdown]](04-variational-inference)
5. Introduction to AgentTorch: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/05-predator-prey.ipynb)[[Markdown]](05-predator-prey)
6. Advanced AgentTorch API: [[Colab]](https://colab.research.google.com/github/arnauqb/diff_abms_tutorial/blob/main/notebooks/06-agent-torch.ipynb)[[Markdown]](06-agent-torch)



# Presenters

[Arnau Quera-Bofarull](https://www.arnau.ai) is a postdoctoral researcher at the Department of Computer Science of the University of Oxford.

[Joel Dyer]() is a senior postdoctoral researcher at the University of Oxford’s Department of Computer Science and a Senior Research Fellow at the Oxford Institute for New Economic Thinking. 

[Nick Bishop]() is a postdoctoral researcher at the University of Oxford working on the large agent collider (LAC) project.

[Imran Mahmoood]() is a senior postdoctoral researcher at the Department of Computer Science, University of Oxford. 

[Ayush Chopra](https://www.media.mit.edu/people/ayushc/overview/) is a PhD student at the MIT Media Lab.

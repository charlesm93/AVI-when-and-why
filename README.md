# AVI-when-and-why
Code to reproduce experiments in paper: "Amortized Variational Inference: When and Why?" by Charles Margossian and David Blei.

Preprint: https://arxiv.org/abs/2307.11018
Talk (now a little dated): https://www.youtube.com/watch?v=vluu7BxA6js

## Overview
This code can be used to reproduce the results and plots in Section 4 "Numerical Experiments" of the paper. For each model, run the notebook with the corresponding name. Experiment results are saved in `deliv` and `deliv_vae`, and figures are saved in `to_discuss`. I uploaded results for the Bayesian VAE and figures for the paper. To get experiment results for the linear and nonlinear probabilistic model, and saw times model, run the corresponding notebooks. The runtime is reasonable, and should take between minutes to an hour, depending on how many seeds you use. The Bayesian VAE experiment takes a bit less than 10 hours for 10 seeds.






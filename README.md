# AVI-when-and-why
Code to reproduce the experiments in the paper: "Amortized Variational Inference: When and Why?" by Charles Margossian and David Blei. 

Preprint: https://arxiv.org/abs/2307.11018


## Overview
This code can be used to reproduce the results and figures in Section 4 "Numerical Experiments" of the paper. There are four models:

* linear probabilistic model
* Nonlinear probabilistic model
* Bayesian neural network
* Sawtime series

For each model, run the notebook with the corresponding name. Experimental results are saved in a `deliv` directory (the first time you run this code, you will need to create this directory). Each notebook also contains code which reads in the experimental results and generates the figures used in the paper.





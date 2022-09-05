---
title: "ALIENs and Continuous Time Economies"
collection: research
permalink: /research/paper2
excerpt:
date:
venue:
paperurl: 'http://goutham-epfl.github.io/website/files/paper2.pdf'
citation:

<ins>__Abstract__</ins> : I develop a new computational framework called Actively Learned and Informed Equilibrium Nets (ALIENs) to solve continuous time economic models with endogenous state variables and highly non-linear policy functions. I employ neural networks that are trained to solve supervised learning problems that respect the laws governed by the economic system in the form of general parabolic partial differential equations. The economic information is encoded as regularizers that disciplines the deep neural network in the learning process. The sub-domain of the high dimensional state space that carries the most economic information is learned actively in an iterative loop, enforcing the random training points to be sampled from areas that matter the most to ensure convergence. I utilize a state-of-the art distributed framework to train the network that speeds up computation time significantly. The method is applied to successfully solve a model of macro-finance that is notoriously difficult to handle using traditional finite difference schemes.

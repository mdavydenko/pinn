## Readme

A small sandbox to test and try physics informed neural network.

Reproduces the approach from the following paper: https://arxiv.org/abs/2006.11894

First, the wavefield is simulated using Devito package.
Then a subset of modeled wavefields is used to train the NN. The second penalty term in the objective function is responsible for applying 'PDE rules' in NN

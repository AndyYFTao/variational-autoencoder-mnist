# Variational Autoencoders
#### UofT STA414 Winter 2020 A3
#### Instructors: David Duvenaud and Jesse Bettencourt

**Background** 
We will implement and investigate the Variational Autoencoder on binarized MNIST
digits, as introduced by the paper Auto-Encoding Variational Bayes by Kingma and Welling (2013): https://arxiv.org/pdf/1312.6114.pdf

This repository contains the following files:

* `.gitignore` - tells git to ignore certain kinds of files. This prevents you from submitting the auxiliary files created when producing LaTeX documents.
* `README.md` - the text you are currently reading.
* `A3.tex` LaTeX source for the writeup.
* `A3.pdf` assignment text compiled from tex. Please replace with your solutions. Feel free to use Weave.jl 
* `Project.toml` packages for the Julia environment.
* `vae.jl` starter code for assignment in Julia.
* `example_flux_model.jl` code which illustrates how to use Flux.jl
* `variational_autoencoder.py` starter code if you would like to use Python with autograd.
* `loadMNIST.py` utility functions of python loading data.

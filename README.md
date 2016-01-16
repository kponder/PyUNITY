# PyUNITY
Python implementation of UNITY

# About
The Unified Nonlinear Inference for Type-Ia cosmologY (UNITY) by David Rubin et al (http://arxiv.org/abs/1507.01602) is a Bayesian framework to account for statistical and systematic uncertainties in supernova cosmological analyses. 

UNITY is currently implemented in STAN which runs a Hamiltonian Monte Carlo (HMC) sampling method. Unfortunately, STAN is not compatible with Python and Python libraries (such as AstroPy or SNCosmo).

This is the effort to implement UNITY in Python using a range of Bayesian methods, such as importance sampling, and samplers, such as emcee and PyMC3.

# Methods
We plan to create Probabilistic Graphical Models (PGMs) of increasing complexity to test the framework implementation and the systematic modeling put in place. 





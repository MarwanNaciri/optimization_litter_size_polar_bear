# Optimization_of_litter_size_in_polar_bears
Marwan Naciri, Jon Aars, Magnus Andersen, Marie-Anne Blanchet, Andrew E. Derocher, Marlène Gamelon, Øystein Wiig, and Sarah Cubaynes. 2025. Data and code for "Offspring number, size, and survival: state-dependent optimization of litter size in a long-lived capital breeder".

[![DOI](https://zenodo.org/badge/1018603336.svg)](https://doi.org/10.5281/zenodo.15870511)

The Rmardown file PA_CR.Rmd contains the full workflow of the analysis presented in Naciri et al. (2025). Specifically, the workflow involves:
- building the model in a Bayesian framework
- generating the input data and initial values for the model
- fitting the model with MCMC using nimble
- checking the output (trace plots & Rhat)
- computing quantities of interest (predictions, observations corrected for the effect of a given set of variables, etc.)
- quantifying the level of evidence for effects
- plotting the main figures.

The model takes ~6 hours to run on an HPC cluster, but the output of the model is also included in this repository.


Software and package version:
R version 4.3.0
nimble version 1.1.0
tidyverse version 2.0.0
patchwork version 1.2.0
Rstudio version 2024.9.1.394

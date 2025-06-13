# Bayesian parameter estimation using stochastic sampling


## Plan

1. Demonstration of Nested Sampling
1. Basic straight line fit and model comparison
1. BBH 4 parameter tutorial
1. BNS 4 parameter tutorial with tidal deformabilities
1. Hierarchical inference of mass distribution using GWTC-3 events



# Setup

## Using PC (recommended)

1. Use the `environment.yaml` file in `nbs` directory and anaconda/miniconda:

`conda env create -f environment.yaml`


1. Activate the environment

`conda activate np3m`


## Using Google Collab

1. Access the [notebooks here](https://drive.google.com/drive/folders/1mnpEiPGslupK0leCbBySvaTp4jhkPaDh?usp=sharing)
1. Execute the approriate cell to install the requisite packages.


## References
1. [pycbc](https://pycbc.org/) for generating waveforms, bayesian inference PE on GW events.
1. [bilby](https://github.com/bilby-dev/bilby) A multi sampler equipped Bayesian PE tool, primarily developed for GW inference.
1. [gwpopupation](https://github.com/ColmTalbot/gwpopulation) A python package to carry out Bayesian Hierarchical inference to infer population properties of CBC events.
1. [dynesty](https://dynesty.readthedocs.io/en/v2.1.5/) A dynamic nested monte carlo sampler.




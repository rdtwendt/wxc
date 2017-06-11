# wxc

## Atmospheric Prediction with Bayesian Inference and MCMC Sampling

This notebook represents a portion of my Ph.D. research in [statistical post-processing](https://www.weather.gov/mdl/statpp_home) of continuous weather variables with [Bayesian inference](https://en.wikipedia.org/wiki/Bayesian_inference) and [Markov chain Monte Carlo](https://en.wikipedia.org/wiki/Markov_chain_Monte_Carlo) methods. A principle aim is to establish a hierarchical multivariate [Bayesian approach](https://www.nr.no/~thordis/files/Richter2012.pdf) to [ensemble model output statistics](http://journals.ametsoc.org/doi/pdf/10.1175/MWR2904.1) (EMOS) with an [adaptive](http://probability.ca/jeff/ftpdir/adaptex.pdf), [block-wise](https://theclevermachine.wordpress.com/2012/11/04/mcmc-multivariate-distributions-block-wise-component-wise-updates/) variant of the [Metropolis algorithm](https://en.wikipedia.org/wiki/Metropolis%E2%80%93Hastings_algorithm) as a computationally economical alternative to traditional ensemble prediction systems (EPS). It may also be used to generate probabilistic forecasts for response variables not represented in the model's [predictor variables](http://onlinestatbook.com/glossary/predictor.html).

### Current Notebooks

  - <a href="https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/NPSMDL_WxC.ipynb" target="_blank">Full Model Code</a>

### Deprecated Notebooks

  - <a href="https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/wxc_theta_post.ipynb" target="_blank">Posterior Inference</a>

  - <a href="https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/mcmc_arcn_chain_0.ipynb" target="_blank">Metropolis Sampler</a>

## Abstract

- Ensemble predictions of sensible weather variables often manifest coherent patterns of forecast error. While the numerical weather prediction community has traditionally focused on improvements to upstream model components – that is, the sophistication of various data assimilation schemes, more detailed mathematical descriptions of the governing dynamics, advanced numerics, and improved fidelity in parameterizing subgrid-scale processes via model physics – comparatively little attention has been given to post-processing techniques that diagnose and calibrate systematic forecast errors downstream of the objective guidance. In this way, statistical post-processing exploits correlations between forecasts and their corresponding observations to improve the quality of contemporary predictions. This dissertation will explore the efficacy of existing methods in Bayesian analysis and Markov chain Monte Carlo sampling to produce statistically post-processed forecasts of continuous sensible weather variables in three disparate forecast applications. More specifically, a hierarchical Bayesian multiple linear regression framework will be pursed for multivariate predictions. An adaptive multiparameter variant of the Metropolis algorithm will be used to draw samples from Bayesian posterior distributions of generative model parameters. Posterior predictive distributions (PPD) will subsequently be formed from contemporary ensemble guidance, and evaluated with distributions-oriented scoring rules, to produce reliable and sharp forecast distributions.

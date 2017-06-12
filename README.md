# wxc

<a href="https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/NPSMDL_WxC.ipynb"><img src="https://dl.dropboxusercontent.com/u/88590382/html_pics/wxc_splash.jpg" style="width:600x"></a>

## Atmospheric Prediction with Bayesian Inference and MCMC Sampling

This notebook represents a portion of my Ph.D. research in [statistical post-processing](https://www.weather.gov/mdl/statpp_home) of continuous weather variables with [Bayesian inference](https://en.wikipedia.org/wiki/Bayesian_inference) and [Markov chain Monte Carlo](https://en.wikipedia.org/wiki/Markov_chain_Monte_Carlo) methods. A principle aim is to establish a [hierarchical](https://en.wikipedia.org/wiki/Bayesian_hierarchical_modeling) [multivariate](https://en.wikipedia.org/wiki/Bayesian_multivariate_linear_regression) [Bayesian approach](https://www.nr.no/~thordis/files/Richter2012.pdf) to [ensemble model output statistics](http://journals.ametsoc.org/doi/pdf/10.1175/MWR2904.1) (EMOS) with an [adaptive](http://probability.ca/jeff/ftpdir/adaptex.pdf), [block-wise](https://theclevermachine.wordpress.com/2012/11/04/mcmc-multivariate-distributions-block-wise-component-wise-updates/) variant of the [Metropolis algorithm](https://en.wikipedia.org/wiki/Metropolis%E2%80%93Hastings_algorithm) as a computationally economical alternative to traditional ensemble prediction systems (EPS). It may also be used to generate probabilistic forecasts for response variables not represented in the model's [covariates](https://en.wikipedia.org/wiki/Covariate).

## Project Notebooks

#### Current

  - [WxC Model Code](https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/NPSMDL_WxC.ipynb)

#### Deprecated

  - [Posterior Inference](https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/wxc_theta_post.ipynb)

  - [Metropolis Sampler](https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/mcmc_arcn_chain_0.ipynb)
  
## Technical Support

#### Jupyter Notebooks

- [Notebook Viewer](https://nbviewer.jupyter.org/) ([FAQ](https://nbviewer.jupyter.org/faq))

- [Notebook Gallery](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)

#### Python Installation

- [Anaconda](https://www.continuum.io/downloads): An Open Platform for Data Science in Python

#### Helpful bootstrapping tutorials on Python, important modules, and related coding cookbooks

- [A modern guide to getting started with Data Science and Python](http://twiecki.github.io/blog/2014/11/18/python-for-data-science/) via [Thomas Wiecki](https://twitter.com/TWiecki)

- [Quick Python Intro](http://nbviewer.jupyter.org/github/barbagroup/AeroPython/blob/master/lessons/00_Lesson00_QuickPythonIntro.ipynb) via [AeroPython](https://github.com/barbagroup/AeroPython)

- [10 Minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/10min.html)

- [Seaborn: statistical data visualization](https://seaborn.pydata.org/index.html)

- [Matplotlib](https://matplotlib.org/): MATLAB-like plotting library

- [Notes on Data Science, Machine Learning, & Artificial Intelligence](https://chrisalbon.com/#Python) via [Chris Albon](https://twitter.com/chrisalbon?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)

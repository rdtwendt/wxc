# wxc

<a href="https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/NPSMDL_WxC.ipynb"><img src="https://dl.dropboxusercontent.com/u/88590382/html_pics/wxc_splash.jpg" style="width:600x"></a>

## A Hierarchical Multivariate Bayesian Approach to Ensemble Model Output Statistics in Atmospheric Prediction

This notebook represents a portion of my Ph.D. research in [statistical post-processing](https://www.weather.gov/mdl/statpp_home) with [Bayesian inference](https://en.wikipedia.org/wiki/Bayesian_inference) and [Markov chain Monte Carlo](https://en.wikipedia.org/wiki/Markov_chain_Monte_Carlo) sampling methods. A principal objective of this research is the development of a computationally economical alternative to traditional ensemble prediction systems (EPS) with a [hierarchical](https://en.wikipedia.org/wiki/Bayesian_hierarchical_modeling) [multivariate](https://en.wikipedia.org/wiki/Bayesian_multivariate_linear_regression) Bayesian approach to [ensemble model output statistics](http://journals.ametsoc.org/doi/pdf/10.1175/MWR2904.1) - that is, [BEMOS](https://www.nr.no/~thordis/files/Richter2012.pdf) - when paired with an [adaptive](http://probability.ca/jeff/ftpdir/adaptex.pdf) variant of the [Metropolis algorithm](https://en.wikipedia.org/wiki/Metropolis%E2%80%93Hastings_algorithm) using [block-wise](https://theclevermachine.wordpress.com/2012/11/04/mcmc-multivariate-distributions-block-wise-component-wise-updates/) multidimensional parameter updates. It may also be used to generate probabilistic forecasts for response variables not represented in the model's [covariates](https://en.wikipedia.org/wiki/Covariate) (e.g., [surface spectral reflectance](https://modis.gsfc.nasa.gov/data/dataprod/mod09.php) inferred from model fields for [low-cloud fraction](https://en.wikipedia.org/wiki/Cloud_fraction), [relative humidity](https://en.wikipedia.org/wiki/Relative_humidity), and [$\omega$](https://en.wikipedia.org/wiki/Omega_equation) via [NowCast](https://github.com/rdtwendt/nowcast)).

## Project Notebooks

#### Current:

 - [WxC BEMOS](https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/NPSMDL_WxC.ipynb) [[ZIP](https://github.com/rdtwendt/wxc/archive/master.zip)]
 
#### Deprecated:

- [Posterior Inference](https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/wxc_theta_post.ipynb)

- [Metropolis Sampler](https://nbviewer.jupyter.org/github/rdtwendt/wxc/blob/master/notebooks/mcmc_arcn_chain_0.ipynb)
  
## Technical Support

#### Python Installation:

- [Anaconda](https://www.continuum.io/downloads): An Open Platform for Data Science in Python

#### Jupyter Notebooks:

- [Jupyter](http://jupyter.org/)

- [Notebook Viewer](https://nbviewer.jupyter.org/)

- [Notebook Gallery](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)

#### Helpful bootstrapping tutorials on Python, important modules, and related coding cookbooks:

- [A modern guide to getting started with Data Science and Python](http://twiecki.github.io/blog/2014/11/18/python-for-data-science/) via [Thomas Wiecki](https://twitter.com/TWiecki)

- [Quick Python Intro](http://nbviewer.jupyter.org/github/barbagroup/AeroPython/blob/master/lessons/00_Lesson00_QuickPythonIntro.ipynb) via [AeroPython](https://github.com/barbagroup/AeroPython)

- [10 Minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/10min.html)

- [Seaborn: statistical data visualization](https://seaborn.pydata.org/index.html)

- [Matplotlib](https://matplotlib.org/): MATLAB-like plotting library

- [Notes on Data Science, Machine Learning, & Artificial Intelligence](https://chrisalbon.com/#Python) via [Chris Albon](https://twitter.com/chrisalbon?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)

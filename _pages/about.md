---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am an Assistant Professor at the University of Connecticut in the Department of Statistics.


My current research is primarily on the application of deep learning to problems in Climatology and Epidemiology and on developing robust tools for applying deep learning models in scientific contexts. Ongoing work develops analyzes and post-processes climate model output with deep neural networks,  tools for granger causality and policy evaluation with differentiable models, forecasts West Nile virus with graph neural networks, and more. Past research includes work in functional data analysis, anomaly detection, change point detection, and robust nonparametric hypothesis testing.

## Positions
I am currently looking to support a PhD student to work on conformal inference for high dimensional / functional regression problems for applications in climate and weather forecasting. This work will be in close collaboration with Sandia National Labs. Must be U.S. Citizen (per grant requirements).


## Ongoing work

### Deep learning for Climate
Currently working on the problem of combining (integrating) ensembles of spatial climate model output into a single projection with uncertainty. We demonstrated that Neural Network Gaussian Processes are an effective tool for combining ensembles of climate models into a single projection, which signficantly reduced forecasting error for temperature in the near future (2020-2060) and for precipitation over the entire projection period (2020-2100). We are working on methods to replace the NNGP with finite-width networks to further improve far future forecasting error, by mitigating distribution shift, and methods to rigorously quantify uncertainty over the predicted fields. We are also investigating methods for uncovering transferrable, i.e. invariant under distribution shift, subspaces that can be used to improve generalization.


### Causality and Granger causality
My group is working on two directions: Estimation of generalized causal contrasts using blackbox models and identifying Granger causality from deep neural networks. We are working to show that scoring rules lead to valid causal contrasts and allow for the identification of different types of distributional causal effects in non-standard time series, such as dynamic networks, functional time series, and count time series. We are applying this methodology to study the effects of extreme weather (interventions) on mosquito infection rates. We are also developing tools to estimate and test for Granger causality through deep neural networks to scale Granger causality to high-dimensional non-linear problems.

### Vector Borne Disease modeling
My group is also developing Graph Neural Network based models for forecasting incidents of West Nile virus using high resolution weather and remote sensing data. Early results showed that imposing a spatial graph on mosquito trap locations and using a GNN to handle spatial message passing significantly improved predictive skill over existing approaches. Ongoing research is trying to extend this approach to allow for massive spatiotemporal covariates at each node (trap site) and to estimate more appropriate spatial graphs that can account for teleconnections and possible heterphilic behavior.

### Climate model validation and analysis
We also work on problems in climate model validation, detection and attribution, and climate model emulation. We are currently developing two computationally efficient sliced metrics for comparing distributions of climate model output, a two-stage sequential analysis method for detecting and attributing climate change to anthropogenic forceings, and tools for climate model emulation based on Bayesian transport maps.



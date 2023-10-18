---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am an Assistant Professor in the Statistics Deparment at Texas A&M University.

My research interests broadly include spatiotemporal modeling, functional data analysis, anomaly detection, and Bayesian deep learning. Much of my work is driven by problems in Climatology, Environmental Science, and Public Health. Current projects apply Deep Learning to data fusion problems, develop uncertainty techniques for deep models, and model vector borne diseases. 


## Ongoing work

### Deep learning for Climate
Currently working on the problem of combining (integrating) ensembles of spatial climate model output into a single projection with uncertainty. We demonstrated that Neural Network Gaussian Processes could be used to significantly reduce forecasting error for temperature in the near future (2020-2060) and for precipitation over the entire SSP projection period (2020-2100). We are working on methods to replace the NNGP with finite-width networks to further improve far future forecasting error by mitigating distribution shift and methods to rigorously quantify uncertainty over the predicted fields. We are also investigating methods for uncovering transferrable, i.e. invariant under distribution shift, subspaces that can be used to improve generalization.

### Causality and Granger causality
My group is working on two directions: Estimation of generalized causal contrasts using blackbox models and identifying Granger causality from deep neural networks. Developing a scoring approach to causal constrast estimation to allow for the identification of causal effects in non-standard time series, such as dynamic networks, functional time series, and count time series. Currently applying this methodology to student the effects of extreme weather (interventions) on mosquito infection rates. Also developing tools to estimate and test for Granger causality through deep neural networks to scale Granger causality to high-dimensional non-linear problems.

### Vector Borne Disease modeling
My group is also developing Graph Neural Network based models for forecasting incidents of West Nile virus in Illinois. Eerly results showed that imposing a spatial graph on mosquito trap locations and using a GNN to handle spatial message passing significantly improved predictive skill over existing approaches. Ongoing work is trying to extend this approach to allow for spatiotemporal covariates at each node (trap site).

### Climate model validation
We also work on problems in climate model validation, detection and attribution, and climate model emulation. We are currently developing two computational efficient sliced metrics for comparing distributions of climate model output, a two-stage sequential analysis method for detecting and attributing climate change to anthropogenic forceings, and tools for climate model emulation based on Bayesian transport maps.



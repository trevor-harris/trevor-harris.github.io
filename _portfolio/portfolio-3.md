---
title: "Segmenting locally stationary time series"
excerpt: "Fused Lasso with CUSUM to identify change points <br/><img src='/images/fcp/region3.png'>"
collection: portfolio
---


We introduced a very fast method to estimate multiple change points from time series data. We first use a fused lasso to identify possible change points. However, because fused lasso tends to overestimate the number of change points, we introduced an aggregation scheme to merge nearby change points into change _sets_. We then use the boundaries of the change sets to define subregions and apply CUSUM with each region to identify the change point within each region. Whats nice is that this method is accurate and only requires one pass over the data to compute the fused lasso, then slightly less than two passes to find each change point.
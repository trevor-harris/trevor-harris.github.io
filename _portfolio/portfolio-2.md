---
title: "Graph Neural Networks for West Nile virus"
excerpt: "Dynamic graphs of WNV mosquito traps <br/><img src='/images/gnn_mosquito/chicago_traps_graph_5_col.pdf'>"
collection: portfolio
---


Here we introduced a GNN model for forecasting trap positivity. Each week a random set of traps are checked for WNV positivity in Illinois, but there is not enough budget to check each trap each week. We view the set of checked traps as a dynamic graph, where the node set and edge set change (to vary degrees) at each time step. We use define the edge set by connecting $k$-nearest neighbors. Each week we make a prediction of whether WNV will be observed at that trap at any time in the next 1 to 7 weeks.

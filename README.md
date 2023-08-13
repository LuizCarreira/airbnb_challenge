# airbnb_challenge

This repository includes the code and the data sets used to solve the `airbnb listings` challenge.

The pipeline contains five steps: data cleaning, data analysis, clustering, visualization, and statistics tests.
For each step, we've created a file. Each file contains all the code to perform some task. For example, the
`data_analysis_airbnb_challenge.ipynb` file performs the data analysis, and so on.

We've employed the K-means algorithm to perform the clustering. We've tried the DBSCAN algorithm. But, the
K-means is preferred over DBSCAN because the clusters are more distinguishable.

We've executed the clustering step twice. First, we've only used numerical variables. This first step
is focused, mainly, on latitude and longitude features. Then, we used the returned clusters of the first step and categorical/numerical variables to do the clustering again in order to get a better segmentation.


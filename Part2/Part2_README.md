This folder contains the code for the second part of the Master's Thesis. Below, the code files in this folder are listed along with a brief description of their functionality.
1. R code for clustering:  
   **1.1. Clustering code with Euclidean distance**: Groups SDG2 data from 27 countries into 2 clusters using k-means, evaluates the clustering quality with the Silhouette Score, and displays a visualization of the results. It can also be applied to other SDGs by simply changing the corresponding data matrix.
   
   **1.2. Clustering code with DTW distance**: Demonstrates DTW for comparing time series: first aligning and plotting two example series, then applying k-means with DTW distance on the SDG2 series to group them into 2 clusters. It can also be applied to another SDG by simply replacing the corresponding dataset.
   
3. **R code for the VAR(p) model**: The code loads time series data for four SDGs, tests for stationarity, applies necessary transformations, selects the optimal lag, conducts Granger causality tests, and fits a VAR model with 3 lags. It can be adapted for other SDGs by modifying the data inputs.

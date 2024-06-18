## README Stock Clustering
For this project, I will use the K-means algorithm and clustering optimization techniques to cluster stocks to determine a portfolio investment strategy.

## Steps

1. Run the code that creates a DataFrame from the stock_data.csv file.

2. Run the code that scales the df_stocks DataFrame and creates a new DataFrame that contains both the scaled and encoded data.

3. Initialize the K-means model with three clusters and then fit the df_stocks_scaled DataFrame to the model.

4. Predict the clusters and then create a new DataFrame with the predicted clusters.

5. Create a scatter plot to visualize the "StockCluster" using "MeanOpen" as the x-variable and "MeanPercentReturn" as the y-variable.

6. Reduce the number of features to two principal components on the df_stocks_scaled DataFrame, and calculate the explained variance ratio that results from the principal component analysis (PCA) data.

7. Use the calculated PCA DataFrame from Step 6 to create a new DataFrame called df_stocks_pca, and then add an additional column to the df_stocks_pca DataFrame that contains the tickers from the original df_stocks DataFrame.

8. Rerun the K-means algorithm on the df_stocks_pca DataFrame and create a scatter plot using the "StockCluster" and the two principal components for the x- and y-axes, then answer the following:
  *After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

9. Determine which features have the strongest or weakest influence on each principal component.

10. Create a scatter plot of the most influential features for each principal component and stock cluster.


## Reference
Brown, M. 2014. Dow Jones Index. UCI Machine Learning Repository. Available: https://archive.ics.uci.edu/dataset/312/dow+jones+index [2023, September 25] (CC-BY 4.0).


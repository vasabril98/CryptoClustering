# CryptoClustering

# Background
In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

# Instructions
In this challenge the following was accomplished:
* Data was given as a csv file then normalized and coverted to a dataframe
  ![scaled_data](https://github.com/vasabril98/CryptoClustering/blob/main/Images/scaled_data.png)
* The best value for k was found using the original scaled dataFrame
  ![elbow_plot1](https://github.com/vasabril98/CryptoClustering/blob/main/Images/elbow_plot1.png)
* The cryptocurrencies were clustered  with K-means using the original scaled data
  ![kmeans_plot1](https://github.com/vasabril98/CryptoClustering/blob/main/Images/kmeans_plot1.png)
* The clusters were optimized with Principal Component Analysis
   ![pca_data](https://github.com/vasabril98/CryptoClustering/blob/main/Images/pca_data.png)
* The best value for k was found using the PCA data
  ![elbow_plot2](https://github.com/vasabril98/CryptoClustering/blob/main/Images/elbow_plot2.png)
* The Cryptocurrencies were clustered with K-means using the PCA data
  ![kmeans_plot2](https://github.com/vasabril98/CryptoClustering/blob/main/Images/kmeans_plot2.png)

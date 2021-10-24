# Cryptocurrencies
## Overview
The purpose of this analysis is to group all the crypto currencies that are currently trading into clusters. For this analysis we will use unsupervised Machine Learning Methods such as PCA and Kmeans. 
## Results
1. PCA Method: After we scaled the data, we used PCA method to reduce the data to 3 principal components for each crypto currency. 
2. Elbow Curves:  We then use the inertia algorithm to plot the elbow curve and determine that the ideal number of clusters is four (4) (k=4).
3. Kmeans Model:  Using four (4) clusters (k=4), the Kmeans model was run and the results where plotted, as shown below. Take note that most of the crypto currencies are within three (3) clusters. 
4. Crypto Currency Mined vs Supply:
Next, we investigated the Mined vs supply side of each class to see if there was any correlation between classes and notice there was none. 

## Summary 
Using the PCA method, Elbow Curve, and the Kmeans method we were able to cluster all the crypto currencies being traded into four (4) clusters. In retrospect, three (3) clusters could have been sufficed since there was one cluster with 1 crypto currency. Additionally, we tried to see if there was any correlation between the cluster class and crypto mined/supply rates and notice no correlation. 
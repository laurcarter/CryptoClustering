# Crypto Clustering

This code applies K-Means clustering and Principal Component Analysis (PCA) to group cryptocurrencies based on their price changes over various time periods. The goal is to determine the best number of clusters, reduce the data dimensions using PCA, and visualize the results.

## Notes on Warnings
While working on this project, I encountered some FutureWarning messages related to Scikit-learn. To suppress these warnings, I used the following code at the start of the notebook:

import warnings

warnings.filterwarnings('ignore', category=FutureWarning)

I found this solution from [StackOverflow](https://stackoverflow.com/questions/57979845/how-do-i-remove-future-warning-regarding-n-estimators-will-change-from-10-in-ver).

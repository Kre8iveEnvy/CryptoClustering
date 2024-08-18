# CryptoClustering
In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Original data set is provided in the format of a csv 
Reference Resources folder for [crypto_market_data.csv](https://github.com/Kre8iveEnvy/CryptoClustering/blob/main/Resources/crypto_market_data.csv)

## Final IPYNB project file Crypto_Clustering.ipynb
Reference main branch [Crypto_Clustering.ipynb](https://github.com/Kre8iveEnvy/CryptoClustering/blob/main/Crypto_Clustering.ipynb)
- Jupyter notebook was the application used and contains the live code, equations, visualizations and narrative text using the Python extension. 
- libraries and dependencies used
    -  import pandas as pd
    -  import hvplot.pandas
    - from sklearn.cluster import KMeans
    - from sklearn.decomposition import PCA
    - from sklearn.preprocessing import StandardScaler

## Instructions
-  Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file
-  Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
-  Find the Best Value for k Using the Original Scaled DataFrame
- Cluster Cryptocurrencies with K-means Using the Original Scaled Data
- Optimize Clusters with Principal Component Analysis
- Find the Best Value for k Using the PCA Data
- Cluster Cryptocurrencies with K-means Using the PCA Data



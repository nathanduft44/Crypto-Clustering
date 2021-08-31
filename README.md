# Crypto-Clustering
Unsupervised Machine Learning of Cryptocurrency closing price data with SCikit-Learn preprocessing, KMeans clustering and normalizing the data for analysis. Visualizations with Pandas HvPlot.
## Purpose
With the use of a vast amount of cryptocurrencies and tokens generated from the API, I used the KMeans algorithm to help classify the crypto into distinct and useful clusters that show patterns of price performance over low and high frequency time frames.
## Technology
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
## Execution
Used Pandas to reduce, scale, and filter the dataset.
 Principle Component Analysis
Used SKLearn to reduce the scaled data to three components for scatterplot.
Used SKLearn KMeans to produce an elbow curve that shows the value that will serve best as the K value in the KMeans model

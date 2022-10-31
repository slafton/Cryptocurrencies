# Cryptocurrencies

## Overview
### Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

### The data will need to be processed to fit the machine learning models. Since there is no known output we will use unsupervised learning. To group the cryptocurrencies, we will use a clustering algorithm. 

## Results

### Clustering Cryptocurrencies Using K-means - Elbow Curve
### ![image](https://github.com/slafton/Cryptocurrencies/blob/main/images/ElbowCurve.png)
### The best K-Value is 4 which is shown by the angle of the line tapering off.

### Visualizing Cryptocurrencies Results
#### 3D Scatter Plot with Clusters
#### ![image](https://github.com/slafton/Cryptocurrencies/blob/main/images/3DScatterPlot.png)
### The 3D scatter plot visualizes the cryptocurrencies with 4 classes after using the principal component analysis algorithm to reduce the cryptocurrencies to three principal components.

#### Tradable Cryptocurrencies Table
#### ![image](https://github.com/slafton/Cryptocurrencies/blob/main/images/TradableCryptoCurrenciesTable.png)
#### This table shows that most of the cryptocurrencies are in class 3 and 0. It also shows that only one cryptocurrency is in class 2, BitTorrent.

#### 2D Scatter Plot with Total Coin Mined vs Total Coin Supply
#### ![image](https://github.com/slafton/Cryptocurrencies/blob/main/images/2DScatterPlot.png)
#### The 2D scatter plot does not efficiently seperate the different classes. The 3D Scatter plut was much easier to see the differences between the clusters.

## Summary
### 532 cryptocurrencies were identified by classs based on the similarities of their features. Now each class is ready to be analyzed to determine their performance and potential interest for the investment bank's clients.
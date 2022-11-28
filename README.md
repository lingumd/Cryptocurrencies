# Cryptocurrencies
## Purpose
Create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data needs to be processed to fit the machine learning models. Since there is no known output, unsupervised learning needs to be used. To group the cryptocurrencies, a clustering algorithm is used. Data visualizations are used to share findings.

### Preprocessing
![](./Images/df1.png)

![](./Images/df2.png)

![](./Images/df3.png)

#### Encoding
![](./Images/encoded.png)

#### Principal Component Analysis
![](./Images/PCA.png)

#### Explained Variance Ratio
![](./Images/ExplainedVarianceRatio.png)

The three principal components explain about 6.983% of the variance in this dataset.

#### Elbow Curve
![](./Images/Elbow_Curve.png)

#### K-Means Model
![](./Images/K-Means.png)

#### Concatenate Dataframe
![](./Images/df4.png)

### Visualizations
#### 3D Scatter Plot of PCA Data and 4 Clusters from clustered_df
![](./Images/3DScatterPCA.png)

#### Hvplot Scatter Plot Using x="TotalCoinsMined" and y="TotalCoinSupply".
![](./Images/hvplot_scatter.png)

#### Hvplot Table with Tradable Currencies 
![](./Images/hvplot_table_screenshot.png)


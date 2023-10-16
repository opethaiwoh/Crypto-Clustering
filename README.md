Cryptocurrency Data Clustering Project

Objective: Analyze and cluster cryptocurrency market data to identify patterns and group similar cryptocurrencies.

Tools & Libraries:

Python Libraries: pandas, hvplot, sklearn
Cloud Platform: Google Colab


Key Steps & Achievements:

Data Loading: Successfully loaded cryptocurrency market data from a Google Drive location, containing various price change percentages for an array of cryptocurrencies.

Exploratory Data Analysis: Conducted preliminary data inspection using .head() and .describe() to understand the dataset's structure. Visualized trends in data using hvplot.line(), providing insights into the cryptocurrency market movements.


Data Preprocessing: Normalized the dataset using the MinMaxScaler from sklearn to ensure consistent data scale across features, a prerequisite for clustering accuracy.


Optimal Cluster Determination: Implemented the Elbow Method to identify the optimal cluster count for K-Means clustering. Determined k=4 as the optimal cluster number, evidenced by the inertia plot.


K-Means Clustering: Applied the K-Means algorithm on the scaled dataset, successfully grouping cryptocurrencies into 4 distinct clusters. Enhanced dataset by appending the model's cluster predictions as a new column.


Data Visualization: Utilized hvplot.scatter() to create a scatter plot, visualizing cluster distributions based on price_change_percentage_24h and price_change_percentage_7d.


Dimensionality Reduction with PCA: Introduced Principal Component Analysis (PCA) to reduce data dimensionality, selecting 3 primary components. Analyzed the explained variance of each component, gaining insights into the significance of the principal components in capturing dataset variance.




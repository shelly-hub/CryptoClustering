# CryptoClustering

## Project Aim
To utilise the knowledge of Python and unsupervised learning to predict the changes of cryptocurrencies.

## Project Description 
Python unsupervised learning is a class of machine learning techniques used to find pattern in data. 
The data to be studied here is crypto data stored in CSV file named as "crypto_market_data.csv"
Jupyter notebook is the main platform to be used to execute unsupervised learning.
The analysis to predict if cryptocurrencies are affected by 24-hour or 7-day price changes would be in "Crypto_Clustering.ipynb"

## Project Method
### Section 01
    1.Open the data, and set "coin_id" as index column
    2. Read the summary statistics of the data and plot to see the most changes variables among all these coin_ids
    3. Scaled all numbered data using  `StandardScaler()` module from scikit-learn
    4. Find best K value from original scaled dataframe
    5. Using the found K-value to plot cluster data for "price_change_percentage_24h"` and "price_change_percentage_7d"`

### Section 02
    6. Using scaled data to perform a principal component analysis (PCA) to reduce the column features to three principal components
    7. Same method as above to find K using PCA data and plot PCA cluster data

### Analysis
    8. Create 2 composite plots: one for Elbow Curve and one for Cluster plots for original scaled data versus PCA scaled data
    9. Identify the behaviour of clusters before optimising (original scaled data) and after optimising (PCA scaled data)

## References
Composing Plots.(2017-2023). Viz. Retrieved on: 10/July/2023, from<https://holoviz.org/tutorial/Composing_Plots.html>
Legend Example.(2005-2023). HoloViews. Retrieved on: 10/July/2023, from<https://holoviews.org/gallery/demos/bokeh/legend_example.html>

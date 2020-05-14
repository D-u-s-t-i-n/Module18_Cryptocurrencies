# Module18 Challenge (Cryptocurrencies)
## Preprocessing
Involves data cleaning such as:
 1. Remove all cryptocurrencies that aren’t trading. 
 2. Remove all cryptocurrencies that don’t have an algorithm defined. 
 3. Remove the IsTrading column. 
 4. Remove all cryptocurrencies with at least one null value. 
 5. Remove all cryptocurrencies without coins mined. 
 6. Store the names of all cryptocurrencies on a DataFramed named coins_name, and use the crypto_df.index as the index for this new DataFrame. 
 7. Remove the CoinName column. 
 8. Create dummies variables for all of the text features, and store the resulting data on a DataFrame named X. 
 9. Use the StandardScaler from sklearn (Links to an external site.) to standardize all of the data from the X DataFrame. Remember, this is important prior to using PCA and K-means algorithms. 

## Reducing Data Dimensions Using PCA
Reduce the dimensions of the X DataFrame down to three principal components.

## Clustering Cryptocurrencies Using K-means
Using elbow curve and determined best K-value of 5.  
KMeans algorithm was used to predict K clusters and create new dataframe clustered_df.

## Visualizing Results
3D Scatter plot shows the principal components are somewhat separated.  
Table and scatter plot shows several coins that are mined. Most mined was BitTorrent.

# cogs118b-final-project



## Jupyter Notebooks 

### cleaning_and_encoding.ipynb

The cleaning_and_encoding notebook contains dataframe cleaning of the csv data and one hot encoding values in certain columns before converting the transformed data into a csv again.

### K_Means_Code-final.ipynb

The K_Means_Code-final notebook contains the different functions that we used in order to implement the K-Means algorithm and to determine the optimal cluster value. 

### Final.ipynb

The Final notebook is an accumulation of the K-Means code and the PCA code, along with plotted PCA components with subsets of 20 datapoints from the data.

### PCA.ipynb

The PCA notebooks contains the functions for the PCA algorithm and verifies the results with a PCA library from sklearn. 


## CSV Files



### clean_data.csv

The clean_data.csv contains the inital scraped data from phonedb.net.

### clustered_data.csv

The clustered_data.cdv contains the final resulting csv that has all of the variables, the principle components and cluster memebership. That is the resulting data from k-means and pca algorithm in csv format.

### encoded_smartphone_data.csv

The encoded_smartphone_data.csv contains the clean_data.csv after it was cleaned and one hot encoded to be used in the K-means and PCA algorithms. 
# unsupervised_ml_cryptocurrencies


This was a great module and challenge overall. The purpose of the challenge was to read in a cryptocurrency dataframe, select the proper data, clean it, then used unsupervised machine learning through KMeans and plot the data. 

- In the selection step, I ensured all coins were live traded coins, removed NA columns, and removed unnecessary columns.

- In the processing data step, I scaled the data points and reduced data dimensions using PCA, principal component analysis, which took the components down to 3.

- In the plotting step, I used a KMeans elbow curve to determine the best K value to use. In this step, a new summary df and a scatterplot df were created.

- The types of data visualization used were a 3d plot, scatter, and a hvplot table.

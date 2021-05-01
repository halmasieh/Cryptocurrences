# Cryptocurrences

## Project Overview
In this analysis, we'll dive deeper into machine learning using unsupervised algorithms, which help us explore data when we're not sure what we're looking for. Now we can analyze data without a clear output in mind. 

The analysis can be perform as the following steps: 
 - Use input data only
 - Process data for unsupervised model
 - Use clustering and K-means algorithm
 - Use principle component analysis (PCA)
 
In fact, we work primarily with the K-means algorithm, the main unsupervised algorithm that groups similar data into clusters. Then, we build on this by speeding up the process using principal component analysis (PCA), which employs many different features.

## Resources
Software: [Jupyter Notebook](https://www.anaconda.com/products/individual)
Module: Pandas, Plotly and Sklearn

## Summary
The cryptocurrency data we will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we are looking for, therefore, we use unsupervised machine learning techniques to analyze data. 
We summarize this analysis as below:

1- Preprocess the dataset in order to perform PCA in step 2, using Pandas.

2- Reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame,  using the Principal Component Analysis (PCA) algorithm.

3- Create an elbow curve to find the best value for K from  DataFrame created in step 2.

4- Run the K-means algorithm to predict the K clusters for the cryptocurrencies data, using K-means algorithm.

5- Visualize the distinct groups that correspond to the three principal components you created in step 2, using scatter plots with Plotly Express and hvplot.

6- Create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

7-Write the README report to describe the purpose of what was accomplished.

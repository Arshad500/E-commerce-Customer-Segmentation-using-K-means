# E-commerce-Customer-Segmentation-using-K-means
Overview
This project aims to segment customers based on their search patterns and past orders. The dataset contains information on customers' gender, number of orders, and their searches for various brands. By clustering customers into distinct groups, we can better understand their preferences and tailor marketing strategies accordingly.

Dependencies
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Yellowbrick
Data
Steps
Data Preprocessing
Load the dataset using Pandas
Inspect the data for duplicates and missing values
Fill missing values with the mode (for the 'Gender' column)
Data Visualization
Create various plots to understand the distribution of data and relationships between variables
Feature Scaling
Scale the features using MinMaxScaler from scikit-learn
Clustering
Determine the optimal number of clusters (k) using the Elbow Method and Silhouette Analysis
Apply KMeans clustering with the optimal k value
Add the cluster labels to the original dataframe
Post-Clustering Analysis
Visualize the distribution of customers in each cluster
Analyze the characteristics of each cluster
Results
The customers have been segmented into distinct groups based on their search patterns and past orders. These insights can be used to develop targeted marketing strategies for each customer segment.

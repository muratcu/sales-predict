# sales-predict
Sales Predict with EDA+Xgboost+KmeansClustering 

We have 3 items and 46 stores and want to predict next day purchase to be able to allocate materials to stores correctly. 

First we cluster all stores based on materials. We will use Kmeans Clustering unsupervised learning algorithm.

After that start oyr Xgboost machine learning algorithm. We first remove outliers from our sales data. 

Then we make brute force for hyperparemeter tuning for each material on each store ( This takes a lot of time and memory. On real-world problems speed is also important. So you can exclude this part from code. )

We visualize feature importance based on gain to determine which variable has most effect on output.

When our prediction finish we compare results based on Clustering group of stores.

The result is below.




You can see there is consistency on output. As algorithm predict higher quantity for stores on cluster A , lower for stores on cluster D...

Good Luck !

# Clustering-for-Unsupervised-learning
There are two parts of data: side view image and front view image.

Both part should do clustering by using kmeans algorithm.

First we design the feature to transform the data

Second we do standscalar or normalizar to preprocess the data

Then we use kmeans algorithm from sklearn to do clustering

Finally I use TSNE to visualize the clustering effect since there are more than three features I design.

By the way, I found the raw data is noisy. I detect the outlier by desinging the new det_outlier features.

Top-30 outlier will be manually detected by the new features.

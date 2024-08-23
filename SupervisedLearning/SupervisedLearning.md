# Supervised Learning

Supervised learning is a kind of machine learning that aims to make predictions about future data based on patterns found within already defined and labelled data. Supervised learning is often used in applications like weather forecasting, or other cases where we want to predict the future or model some (often complex and dynamic) system.

## Linear Regression

Linear regression is a subset of supervised machine learning where we find the line of best fit in some already labelled training data and use this trendline to predict other values. This is particularly useful in data where there is already a strong correlation. Although we only live in four dimensions, can only think in three dimensions spatially, and can only conveniently display two dimensions on screen, linear regression is often done with dozens of inputs that create a set of high-dimensional vectors where the trendline is truly drawn, however, we can only graph two of the values. This allows for much more reliable predictions using a wide variety of variables.

The linear regression algorithm is given labelled 'ground truth' data that it is trying to predict and it is then tuned to predict this value. While most of the data is used for training, as with many types of machine learning it is best to keep some of the data out of the training set to test the AI at the end and prevent overfitting to only the test data.

## KNN Classification

K-Nearest Neighbours (KNN) classification is a form of supervised learning used to find patterns in less structured labelled data. Similar to regression, indeed the KNN algorithm can be used for a different kind of non-linear regression, the KNN algorithm plots the data points in multidimensional vectors. However, unlike regression where a continuous prediction interface is calculated between continuous input fields and continuous output fields, in classification, the output is discrete/integer and often binary e.g. diabetes or no diabetes, spam or not spam etc. 

Each value within the vector space is assigned some discrete class, then, when a new value is added to classify, the KKN algorithm finds the k-nearest neighbours and finds the class with the most points neighbouring the new point. The new point is then predicted to be in this class. This plurality vote system is based on the assumption that points that are near each other in the vector space are more likely to have the same class. This can be useful for quickly classifying new data based on predetermined classes.

However, because KNN classification needs to calculate the distance to all of the points in the vector space, this algorithm doesn't scale exceptionally well in its most basic form for large datasets. Additionally, the discrete nature of the algorithm does mean it can't distinguish the more spectral classifications and doesn't work as well for data that isn't already clearly defined and separated. Finally, by definition, as a supervised learning algorithm it cannot add any categories outside of what it has been taught unlike [K-means clustering](../UnsupervisedLearning).

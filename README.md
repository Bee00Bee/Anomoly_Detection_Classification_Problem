# Anomaly Detection
Anomoly detection breaks into two main categories: 
- Outlier detection.
- Novelty detection.

### 1- Outlier Detection
The concept outlier detection looks simple. By the definition outlier detection means to identify anomolies in the data. For example, you have data which they have a visible trend but there are some data points which don't follow the the trend. These data points might be recorded wrong. So you need to identify these data points. The data points which follow the trend are called *inlier*. 

### 2- Novelty Detection
In *novelty Detection* we like to know whether or not the new observation in the dataset is an outlier. The outlier here is called a novelty. Keep in mind that the data is not pulled out by outliers. 

### Required packages:
* [collections](https://docs.python.org/3/library/collections.html)
* [matplotlib](https://matplotlib.org/)
* [skelrean packages](https://scikit-learn.org/stable/index.html)
  * [make_classification](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_classification.html)
  * [Isolation Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html)
  * [Train Test split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)

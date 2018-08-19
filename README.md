# svm-classification

## Active Learning using SVM
* train SVM by choosing closest data points (10) near hyperplane and repeat
* vs passive learning by choosing random data points (10) in the data pool
* avg the test errors obtained per SVM results in Monte Carlo simulation

## Multi-class and Multi-label Classification using SVM
* train SVM for each label and one-verus-all classifier
* considered linear L1 penalty, rbf kernel
* determine penalty, width of rbf using 10-Fold CV

## Multi-class and Multi-label dataset using K-Means Clustering
* each cluster determined by k-means, determine the majority class for each label (family, genus, species)
* k parameter chosen using CH index (ratio of between-cluster and within-clustervariation)


## note:
* [Banknote Authentication Dataset Link](https://archive.ics.uci.edu/ml/datasets/banknote+authentication#)
* [Anuran Calls (MFCCs) Dataset Link](https://archive.ics.uci.edu/ml/datasets/Anuran+Calls+%28MFCCs%29#)
* python packages includes scikit-learn, numpy, pandas, matplotlib
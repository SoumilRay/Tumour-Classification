# Tumour-Classification

The CSV file contains the data. There are 30 features and the task is to classify a tumour as benign or malignant.


Feature Engineering: 

For some of the data points, one or more feature values are missing 
in the data set. The missing values are imputed with the 
most frequent value in the case of categorical feature with the average 
of the existing values of the corresponding feature if the feature takes continuous numerical 
values.
Normalization of each feature is then done.


PM1: Perceptron Model trained on the non-normalized data
PM2: Same as PM1 but the training examples are shuffled
PM3: Perceptron Model trained on the normalized data
PM4: Same as PM1 but the order of features is changed.

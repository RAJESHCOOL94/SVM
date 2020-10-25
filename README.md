# Linear-SVM-based-email-spam-classifier
This project builds a linear support vector machine (SVM) model to classify emails as spam or ham.

# Data set
The dataset, taken from the UCI ML repository, contains about 4600 emails labelled as 'spam' or 'ham'. The dataset can be downloaded here: https://archive.ics.uci.edu/ml/datasets/spambase

# Data preprocessing
The columns of the raw data set are given as numbers. These column names are manually renamed using the list provided at the UCI website (https://archive.ics.uci.edu/ml/machine-learning-databases/spambase/spambase.names) The data set is further scaled and checked for null values and none are found.

# Model building
SkLearn's SVC() class is used to build a Support Vector Machine model. The  model gives an accuracy of 92.8%.

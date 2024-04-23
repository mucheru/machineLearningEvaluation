# machineLearningEvaluation
# The simplest method that we can use to evaluate the performance of a machine learning algorithm is to use different training and testing datasets.

# We can take our original dataset, split it into two parts. Train the algorithm on the first part, make predictions on the second part and evaluate the predictions against the expected results.

# The size of the split can depend on the size and specifics of your dataset, although it is common to use 67% of the data for training and the remaining 33% for testing.

# This algorithm evaluation technique is very fast. It is ideal for large datasets (millions of records) where there is strong evidence that both splits of the data are representative of the underlying problem. Because of the speed, it is useful to use this approach when the algorithm you are investigating is slow to train.

# A downside of this technique is that it can have a high variance. This means that differences in the training and test dataset can result in meaningful differences in the estimate of accuracy.

# In the example  we split the data Pima Indians dataset into 67%/33% split for training and test and evaluate the accuracy of a Logistic Regression model.

![image](https://github.com/mucheru/machineLearningEvaluation/assets/13763343/a7965dea-ff9a-4db8-b623-1892de545125)

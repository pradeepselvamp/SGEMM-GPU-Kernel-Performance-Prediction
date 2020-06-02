# BUAN 6341: Applied Machine Learning
# SGEMM-GPU-Kernel-Performance-Prediction
Implementing Linear and Logistic regression using Gradient Descent algorithm

A linear regression and logistic regression model implemented using the gradient descent algorithm with batch update (all training examples used at once) having squared error normalized by 2*number of samples [J(β0, β1) = (1/2m)[Σ(yᶺ(i) – y(i))2] as your cost and error measures, to predict the GPU run time. 
The following tasks were carried out:

Part 1: Download the dataset and partition it randomly into train and test set using a good train/test split percentage.
Part 2: Design a linear regression model to model the average GPU run time. Include your regression model equation in the report.
Part 3: Implement the gradient descent algorithm with batch update rule. Use the same cost function as in the class (sum of squared error). Report your initial parameter values.
Part 4: Convert this problem into a binary classification problem. The target variable should have two categories. Implement logistic regression to carry out classification on this data set. Report accuracy/error metrics for train and test sets.




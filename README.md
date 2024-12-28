# insurance_charges_ML_model

This project focuses on fundamental concepts in applied machine learning. It covers the following topics:

1. Data Visualization and Analysis
2. Linear Models for Regression and Classification
3. Support Vector Machines

In this project I implement essential machine learning models, such as Linear Regression (with Ridge Regularization), Logistic Regression, and Support Vector Machines, along with preprocessing, evaluation, and interpretation techniques. This was an assignment for my Applied Machine Learning class.

Tasks and Models
The project begins with data visualization to analyze relationships between features and target variables, using bar plots and scatter plots to gain insights. A custom LinearRegression class is implemented with L2 regularization (Ridge Regression) using the closed-form solution, and the model's performance is evaluated on training, validation, and test datasets using $R^2$ scores. Logistic Regression is implemented with Gradient Descent optimization to handle binary classification, with hyperparameter tuning (learning rate, regularization strength, and epochs) to improve model accuracy. Support Vector Machines (SVMs) are trained using both linear kernels (primal form) and RBF kernels (dual form), with training, validation, and test accuracies compared for both implementations.

Results Summary
For Linear Regression, the most significant predictors of the target variable are smoker, age, and bmi. The scores indicate good model performance, with values of 0.74 for the training set, 0.76 for the validation set, and 0.76 for the test set. Logistic Regression achieves a test accuracy of 0.71% after tuning hyperparameters using Gradient Descent. Support Vector Machines perform well, with both achieving a training accuracy of 0.71% and a test accuracy of 0.71%.

Key Insights
Ridge regularization effectively reduces overfitting in Linear Regression, while Gradient Descent optimizes Logistic Regression parameters, even for imbalanced datasets. The RBF kernel in SVM captures non-linear patterns better than the linear kernel, making it more effective for complex datasets.


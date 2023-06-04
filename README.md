# multiple_linear_regression
This code demonstrates the implementation of Multiple Linear Regression using the given dataset. Here's a step-by-step description of the code:

Importing the necessary libraries: The code begins by importing the required libraries, including numpy, matplotlib, and pandas, which are commonly used for data manipulation and visualization.

Importing the dataset: The dataset is read from a CSV file called '50_Startups.csv'. The independent variables are stored in the 'X' array, and the dependent variable (target) is stored in the 'y' array.

Encoding categorical data: The categorical variable 'State' in the dataset is encoded using the OneHotEncoder class from scikit-learn. This is done to convert categorical data into numerical values so that it can be used in the regression model.

Splitting the dataset: The dataset is split into a training set and a test set using the train_test_split function from scikit-learn. The training set (X_train and y_train) is used to train the regression model, and the test set (X_test and y_test) is used to evaluate the model's performance.

Training the Multiple Linear Regression model: A LinearRegression object is created and fitted to the training data using the fit() method. This step involves finding the optimal coefficients for the linear equation that best fits the data.

Predicting the Test set results: The trained model is used to predict the target variable (profit) for the test set using the predict() method. The predicted values are stored in the 'y_pred' array.

Displaying predicted and actual values: The predicted values ('y_pred') and the actual values ('y_test') are concatenated and printed side by side for comparison.

Making a single prediction: Finally, a single prediction is made using the trained model. The profit of a startup is predicted based on the provided input values: R&D Spend, Administration Spend, Marketing Spend, and State. The result is printed.

The code serves as an example of how to implement Multiple Linear Regression using the scikit-learn library and make predictions using the trained model.

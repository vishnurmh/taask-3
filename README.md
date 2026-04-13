Linear Regression

In this task, I worked on building a linear regression model to understand how different features in the dataset affect a target variable. I used a dataset with numerical features and applied basic preprocessing before training the model.

First, I loaded the dataset using pandas and checked the available columns. Since linear regression works with numerical data, I selected only the numeric columns and removed any missing values to avoid errors during model training.

Next, I separated the dataset into input features and the target variable. The input features are used to predict the output, while the target variable is the value we want to estimate.

After preparing the data, I split it into training and testing sets. The training data is used to train the model, and the testing data is used to evaluate how well the model performs on unseen data.

Then, I created a linear regression model using scikit-learn and trained it using the training dataset. Once the model was trained, I used it to predict values for the test data.

To evaluate the performance of the model, I used three metrics:

Mean Absolute Error (MAE), which shows the average difference between actual and predicted values
Mean Squared Error (MSE), which penalizes larger errors more strongly
R² Score, which indicates how well the model explains the variation in the data

I also plotted a graph comparing actual values and predicted values. This helped me visually understand how close the predictions are to the real values.

In addition to this, I checked the coefficients and intercept of the model. The coefficients show how much each feature influences the target variable, while the intercept represents the base value when all features are zero.

From this task, I understood how linear regression works in practice, how to train a model, and how to evaluate its performance using different metrics. This task also helped me understand the importance of selecting proper features and preparing the data correctly before building a model.

Tools used:
Python, Pandas, Scikit-learn, Matplotlib

Overall, this task gave me a clear understanding of regression modeling and how it can be used for prediction problems.

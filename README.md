## Preparing Data
We start by preparing our data. We split our data into two parts: training data (X_train, y_train) and testing data (X_test, y_test). This helps us train our model and then test how well it works. We use a library called Scikit-learn to split our data.


### Training Model
Next, we train our model using Linear Regression. This type of model helps us predict continuous values, like tip amounts. We teach our model using our training data (X_train, y_train). The model learns how total bill amounts relate to tip amounts.


#### Evaluating Model
After training our model, we evaluate how well it works. We predict tip amounts for our testing data (X_test) and compare these predictions to actual tip amounts (y_test). We calculate three important metrics: Mean Squared Error (MSE), R-squared (R2), and Root Mean Squared Error (RMSE). These metrics tell us how accurate our model is.


###### Visualizing Results
Finally, we visualize our results. We plot our actual data (X_test, y_test) and our predicted line. This helps us see how well our model fits our data. We use a library called Matplotlib to create this plot. By following these steps, we've built and evaluated a Linear Regression model to predict tip amounts based on total bill amounts.

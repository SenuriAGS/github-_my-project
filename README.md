# github-_my-project
import numpy as np
from sklearn.linear_model import LinearRegression

 Sample data
X = np.array([1, 2, 3, 4, 5]).reshape(-1, 1)
y = np.array([2, 4, 5, 4, 5])

Create a linear regression model
model = LinearRegression()

 Fit the model
model.fit(X, y)

 Make predictions
y_pred = model.predict(X)

 Print the coefficients
print("Coefficients:", model.coef_)
print("Intercept:", model.intercept_)

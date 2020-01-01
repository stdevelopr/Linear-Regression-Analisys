# Linear Regression Analysis

Dataset:
The data set contains google stock pricing from the year 2004 up to 2017 which includes opening,closing, high ,low and adjusted stock prices.

---

The main goal is to establish a relation between the date and the closing price, where the date is the independent variable and the closing price is the dependent variable.\
The linear.ipynb file contains the code showing the formula to create a linear regression line and the coefficient of determination R^2:

*Regression line: y = mx+ c*

where the slope (m) formula is given by:\
m= SUM((x-xm)(y-ym))/SUM((x-xm)^2)\
xm and ym are the mean values of the dependent and independent series.

*R² = SUM((y_pred - y_mean)²)/SUM((y - y_mean)²)*\
where y_pred are the predicted values, y_mean is the mean value of the serie and y are the actual values.\

The file also contains how to use the sklearn library to do the same calculations.

After all the code tries to predict the next price of the stock based on a given temporal window, returning the R^2 of the selected interval, and the percentage error in the estimation of the closing price.

Linear Regression: Time Series (Autoregressive) Model for Financial Data
Autoregressive(p) model:

An autoregressive () model predicts future behavior based on past behavior. It’s used for forecasting when there is some correlation between values in a time series and the values that precede and succeed them. An  model is an autoregressive model where specific lagged values of  are used as predictor variables. Lags are where results from one time period affect following periods.

![68747470733a2f2f6f74657874732e636f6d2f667070322f6670705f66696c65732f6669677572652d68746d6c2f6172702d312e706e67-2](https://user-images.githubusercontent.com/119718873/206081011-1f19b236-237e-4aed-a979-9e93cd0e6e59.png)


For example, an  would be a “first order autoregressive process.” The outcome variable in a first order  process at some point in time  is related only to time periods that are one period apart (i.e. the value of the variable at ). An  model can be denoted as below.




Linear regression model:

A linear regression line has an equation of the form Y = a + bX, where X is the explanatory variable and Y is the dependent variable. The slope of the line is b, and a is the intercept (the value of y when x = 0).

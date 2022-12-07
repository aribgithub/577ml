Linear Regression: Time Series (Autoregressive) Model for Financial Data
Autoregressive(p) model:

An autoregressive () model predicts future behavior based on past behavior. It’s used for forecasting when there is some correlation between values in a time series and the values that precede and succeed them. An  model is an autoregressive model where specific lagged values of  are used as predictor variables. Lags are where results from one time period affect following periods.

![68747470733a2f2f6f74657874732e636f6d2f667070322f6670705f66696c65732f6669677572652d68746d6c2f6172702d312e706e67-2](https://user-images.githubusercontent.com/119718873/206081011-1f19b236-237e-4aed-a979-9e93cd0e6e59.png)


For example, an  would be a “first order autoregressive process.” The outcome variable in a first order  process at some point in time  is related only to time periods that are one period apart (i.e. the value of the variable at ). An  model can be denoted as below.



Here, , ...,  are the parameters of the model,  is a constant, and  is white noise.

Linear regression model:

A linear regression model is a linear approach for modelling the relationship between a scalar response and one or more explanatory variables. It can be written as , where  is a vector of observed values .  is a matrix of row-vectors .  is a  dimensional parameter vector, where  is the intercept term.  is a vector of values .

In statistics, ordinary least squares (OLS) chooses the parameters of a linear function of a set of explanatory variables by the principle of least squares: minimizing the sum of the squares of the differences between the observed dependent variable (values of the variable being observed) in the given dataset and those predicted by the linear function of the independent variable. Using OLS,  is obtained through the formula . Accordingly, .

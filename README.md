# Simple Linear Regression
In this project I will be illustrating and documenting the steps of Simple Linear Regression. 
+ This method is an approach for predicting a qualitative response Y on the basis of a single predictor variable X. 
+ This method assumes that there is approximately a linear relationship between X and Y. 

1. Step 1, using the lm() function to fit a simple linear regression model, with medv as the response and lstat as the predictor. 
2. Step 2, using the summary() function to understand the p-value, and standard errors for the coefficients and R^2 Statistic, and F statistic. 
3. Step 3, using the coef() to extract the quantities by name 
4. Step 4, using confint() function to obtain the confidence interval for coefficient estimates 
5. Step 5, using the predict() function to produce the confidence intervals and prediction intervals for a given lstat value (5,10,15)
6. Step 6, plotting medv and lstat along with the least squares regression line 
7. Step 7, Computing the residuals from a linear regression fit with the residuals () function. 

## Packages Used:
##### MASS #### 
+ Contains the Boston.  
+ This dataset contains information collected by the U.S Census Service         concerning housing in the are of Boston,Massachusets.   
+ This dataset will be used to predict median house value (medv) using          13 predictors as average numbers of rooms per house (rm). 
#### ISLR ####
+ Introduction to Statistical Learning with Applications in R.  
# Topics covered in this part.

Complete understanding of linear regression and regularization techniques

a. Lasso
b. Ridge
c. Elasticnet

Also, Understanding of polynomial type of relation inside the linear regression

Imp points:

1. Linear regression means only m and c are required to define relation with y and also its degree will be always 1
2. Polynomial regression will take into account of degree of the equation


# Analyzing Boston House pricing data

1. Load the dataset
2. Target is the label column for the boston pricing data
3. See the characters of each column by plotting distplot
4. see the characteristics by plotting each feature with label data
5. Transform the data to Z scale
6. See if any multi collinearity is present for the data within the features and do some action
7. see the R^2 characteristics and ADJr2 for eliminating features having duplications
8. train_test_split the data from the X and Y data
9. now compare ADJR2 with both test and train data, and if ADJR2 is more for train data and very less for test data then we can say model is overfit
10. To validate the above point, perform regularisation techniques like Lasso and Ridge regression
11. Validate the R2 score with both the models(Linear Regression, Lasso reg, Ridge reg) and find the best model
12. Now load the data into pickle file and use for predicting the model next time for any random data

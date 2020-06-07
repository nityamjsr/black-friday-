# black-friday-
This dataset comprises of sales transactions captured at a retail store. It’s a classic dataset to explore and expand your feature engineering skills and day to day understanding from multiple shopping experiences. This is a regression problem. The dataset has 550,069 rows and 12 columns.
Problem: Predict purchase amount.

Website: https://datahack.analyticsvidhya.com/contest/black-friday/
SOLUTION:1)Now The empty spaces are filled with max value. We also clean or fill empty spaces  of training set(columns:product_category_1,product_category_2)
2)we encode all or categorical data into numerical form which is easy to handle
3)usage of kfold along with PCA is done so as to split data into training set and testing set(PCA is one of the most used and famous dimensionality reduction methods.PCA is for speeding up machine learning algorithms, you are fitting PCA on the training set only. Principal component analysis (PCA)
4) the data is then normalised to get the following benefits
  a)Greater overall database organization.
  b)Reduction of redundant data.
  c)Data consistency within the database.
  d)A much more flexible database design.
  e)A better handle on database security.

PCA replaces original variables with new variables, called principal components, which have zero covariations and have variances in decreasing order. So, the covariance matrix between the principal components extracted from the data.)
5)application of varios regression model in order to get best accuracy.
  a)Linear regression
  b)random forest
  c)Gradient boosting
  d)decision tree
  
6)we recive he following accuracy on training set:
  a)Accuracy Score of Linear regression on train set 11.829233894211866
  b)Accuracy Score of Decision Tree on train set 100.0
  c)Accuracy Score of Random Forests on train set 94.207451077798
  d)Accuracy Score of Gradient Boosting on train set 65.49517152859553
  
7)we recive he following accuracy on testing set:
  a)Accuracy Score of Linear regression on test set 36.8210287243639
  b)Accuracy Score of Decision Tree on test set 57.69794167461
  c)Accuracy Score of Random Forests on test set 76.56294490750602
  d)Accuracy Score of Gradient Boosting on testset 72.43849411693182



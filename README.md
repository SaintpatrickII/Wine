# Wine
Using random forest modelling to predict wine quality

- Data is cleaned With comments on my thought process for certian operations

- wine is classified on quality using random forest model, taking the quality as label

- For this model we are utilising k-fold cross validation for hyperparameter tuning

- For this model we found the BEST PARAMS: {'max_depth': 16, 'n_estimators': 250}, meaning the depth of the random forest is 16 & the number of trees utilised before voting/ taking best average is 250 samples

- Note here we utilise alot of features, for other models with fewer features selected this could drop massively

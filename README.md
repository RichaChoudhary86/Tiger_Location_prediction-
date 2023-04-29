# Tiger_Location_prediction-
Regression code and results for forecasting based on mean of prey location
The results file contains 3 differents scenarios which are mentioned in the researh paper.
## The results_all_tiger_all_prey (case2 from research paper):
 col1: "file name" tells about the case1 i.e. all tigers with all prey 
 col2: "model" -which model is used 
 col3: "MAE" shows Mean Absolute error for that corresponding model 
 col4: "regression Cofficient" for the corresponding model.
 col5: "intercept" for the corresponding model.
 col6: "hidden_first" is the first hidden layer results for MLP model
 col7: "hidden_Second" is the second hidden layer results for MLP model
 col8: "R2"is the coefficient of determination for the models combined for both latitude and longitude.
 col9: "R2_lat" is the coefficient of determination for the models for latitude values only.
 col10: "r2_long" is the coefficient of determination for the models for longitude values only.
 col11: "mean_lat" is the Mean Absolute error for that corresponding model for latitude values only.
 col12: "mean_long" is the Mean Absolute error for that corresponding model for longitude values only.
 ## The results_all_tiger_mul_prey (Case 3 from research paper):
 all columns are same as above file.
 ## The results_specific_tiger_specific_prey (case 1 from research paper)
 all columns are same as above file.

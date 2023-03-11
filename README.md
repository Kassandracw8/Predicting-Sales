# Items Sales in SuperMarket
The analysis of Item Outlet Sales to Item Tpye and Item Visibility


Kassandra Howard


Getting insight from the dataset and to understand how various features play a role in increasing the sales using python with data science.

Data:
Sales predictions : "C:\Users\dhowa\Downloads\sales_predictions - sales_predictions.csv"

Data Dictionary
![image](https://user-images.githubusercontent.com/114174735/224509031-d9b1ea97-687c-4795-8476-8628afa1ccae.png)

There are 8523 rows, 12 columns

Methods

I cleanedand procesed the data and imported the libraies panda, numpy, matlpoltlib, sklearn.tree and sklean.model_selection.

Results

Supermarket 1 Vs Supermarket 2

![image](https://user-images.githubusercontent.com/114174735/224509670-d4989d3f-a652-474f-860e-58f4c5c24eed.png)

This histogram shows that majority item type was sold at Supermarkt 1

Item Type vs.  Sale Price

![image](https://user-images.githubusercontent.com/114174735/224509963-55b6fa33-3606-4833-8a6a-b75f582fe129.png)


The graph show the high visibilty of seafood might have increase sales.

Machine Learning Using the Following Models

Linear Regresion Model

Decision Tree Regressor Model

Tunded Decision Tree Regressor Model

Random Forest Regresspr Model

Tuned Random Forest Regressor Model

Linear Regression Model
Results for training data:
  - R^2 = 0.561
  - MAE = 847.522
  - MSE = 1300414.121
  - RMSE = 1140.357

Results for testing data:
  - R^2 = 0.565
  - MAE = 805.662
  - MSE = 1199404.351
  - RMSE = 1095.173

Decision Tree Regressor
Training Scores for High Variance Decision Tree
Results for training data:
  - R^2 = 0.604
  - MAE = 762.608
  - MSE = 1172166.094
  - RMSE = 1082.666

Testing Scores for High Variance Decision Tree
Results for testing data:
  - R^2 = 0.595
  - MAE = 738.199
  - MSE = 1118159.922
  - RMSE = 1057.431
  
Random Forest Regressor
Training Scores for High Variance Decision Tree
Results for training data:
  - R^2 = 0.939
  - MAE = 295.827
  - MSE = 179905.718
  - RMSE = 424.153



Testing Scores for High Variance Decision Tree
Results for testing data:
  - R^2 = 0.561
  - MAE = 765.896
  - MSE = 1210060.156
  - RMSE = 1100.027
 Random Forest Regression model was chosed with tessting 561.
 
Recommendations:

By the analysis of the given data. The locations of supermarkets  can have high sales. Visibility can be considered as stock. Higher visibility can sell more stock. Less visibility can sell less items.

Limitations & Next Steps

I would recommend more data to be included to the model. The datd predicitions can be a little more accurate.


For further information
Kassandra Howard (Data Scientist)
kassandracw8@msn.com

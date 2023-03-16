# Items Sales in SuperMarket
The analysis of Item Outlet Sales to Item Tpye and Item Visibility


Kassandra Howard


Getting insight from the dataset and to understand how various features play a role in increasing the sales using python with data science.

# Data:
Sales predictions : "C:\Users\dhowa\Downloads\sales_predictions - sales_predictions.csv"

# Data Dictionary
![image](https://user-images.githubusercontent.com/114174735/224509031-d9b1ea97-687c-4795-8476-8628afa1ccae.png)

There are 8523 rows, 12 columns

# Methods

I cleaned and processed the data and imported the libraies panda, numpy, matlpoltlib, sklearn.tree and sklean.model_selection.

# Results

Supermarket 1 Vs Supermarket 2

![image](https://user-images.githubusercontent.com/114174735/224509670-d4989d3f-a652-474f-860e-58f4c5c24eed.png)

This histogram shows that majority items were sold at Supermarkt 1.The Supermarket 1 had a few sales in the 10,000. While Supermarket 2 did not make it into 10,0000 in sales.The highest Supermarket2 did was 6,000.

Item Type vs.  Sale Price

![image](https://user-images.githubusercontent.com/114174735/224509963-55b6fa33-3606-4833-8a6a-b75f582fe129.png)


The graph show the high visibilty of seafood might have increase sales. Seafood had sold $2500. It also had the most visibility. Breakfest has the second items most sold; however,was not high on the visibilty graph.

# Machine Learning Using the Following Models

Linear Regresion Model

Decision Tree Regressor Model

Random Forest Regresspr Model

Tuned Random Forest Regressor Model

 Training Scores for Forest Regressor Model
Results for training data:
  - R^2 = 0.939
  - MAE = 295.827
  - MSE = 179905.718
  - RMSE = 424.153



Testing Scores for Forest Regressor Model
Results for testing data:
  - R^2 = 0.561
  - MAE = 765.896
  - MSE = 1210060.156
  - RMSE = 1100.027
 

 Random Forest Regression model was chosed with tessting 561.
 
# Recommendations:

By the analysis of the given data. The locations of supermarkets  can have high sales. Visibility can be considered as stock. Higher visibility can sell more stock. Less visibility can sell less items.

Limitations & Next Steps

I would recommend more data to be included to the model. The data predicitions can be a little more accurate.


For further information
Kassandra Howard (Data Scientist)
kassandracw8@msn.com

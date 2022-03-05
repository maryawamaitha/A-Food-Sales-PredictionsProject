# A-Food-Sales-PredictionsProject

#This project analyzes a dataset of Various Items sold at different stores.

#The aim of the analysis is to help a retailer planning to open a store on the factors to consider when setting up and which Items to sell based on existing sales.

The dataset includes: 
Item_Weight	Weight of product
Item_Fat_Content	Whether the product is low fat or regular
Item_Visibility	The percentage of total display area of all products in a store allocated to the particular product
Item_Type	The category to which the product belongs
Item_MRP	Maximum Retail Price (list price) of the product
Outlet_Identifier	Unique store ID
Outlet_Establishment_Year	The year in which store was established
Outlet_Size	The size of the store in terms of ground area covered
Outlet_Location_Type	The type of area in which the store is located
Outlet_Type	Whether the outlet is a grocery store or some sort of supermarket
Item_Outlet_Sales	Sales of the product in the particular store. This is the target variable to be predicted.

The library Used include: Numpy, Pandas, Matplotlib, Seaborn and Scikit-learn

The data was first cleaned: by filling the missing values, exploring duplicates and irrelevant information.
Then data visualization was incorporated to show the relationship of the variables

Summary
-Based on the Data Visualizations of the data set: 
1. Supermarket 3 had the highest sales and Location [tier 2] had the highest sales.
2. The grocery stores had the least sales.
3. Items with low fat content were more popular.
4. 
Machine Learning 
To make future prediction on the sales, the data was analysed as Supervised Learning.the training data contains all data variables while test data contains all the variables except the Item Outlet sales(target), which is to be predicted
Two regression models were compared : the Linear Regression and Decision Tree regression model. Based on the results of the two models; Decision tree regression model is recommended as its training data and test data R^2 values are closer(well balanced fit).

# A-Food-Sales-PredictionsProject

#This project analyzes a dataset of Various Items sold at different stores.



https://user-images.githubusercontent.com/97409151/156948023-09d655a5-80f9-496a-ae3a-c5f404a2429d.mp4



#The aim of the analysis is to help a retailer planning to open a store on the factors to consider when setting up and which Items to sell based on existing sales.

The dataset includes: 

    Outlet location
    Outlet Type
    Outlet Size
    Outlet establishment year

Item variables :

    Item idetifier
    Item weight
    Item fat content
    Item visibility
    Item type
    Item MRP
    Item outlet sales


The library Used include: Numpy, Pandas, Matplotlib, Seaborn and Scikit-learn

The data was first cleaned: by filling the missing values, exploring duplicates and irrelevant information.
Then data visualization was incorporated to show the relationship of the variables

From the dataset:The following questions were addressed?

How does the Outlet type affect the Outlet sales?

It was evident Supermarket 3 had highest sales while the grocery store had the least sales.

<img width="323" alt="supermarket" src="https://user-images.githubusercontent.com/97409151/156907378-d5a6f702-3871-44db-a345-2f836dfc0921.PNG">

How does the Oulet location affect the Outlet sales?

Location Teir 2 had the highest Sales.

<img width="384" alt="Location" src="https://user-images.githubusercontent.com/97409151/156907407-e6164bac-832b-405e-ad94-9cd4bd3d4126.PNG">

Which Fat_content was more popular(regular vs low fat)?

<img width="322" alt="fat_content" src="https://user-images.githubusercontent.com/97409151/156907446-36b846b7-4ca4-4d4b-997d-5ac955eaa2b5.PNG">



Summary
-Based on the Data Visualizations of the data set: 
1. Supermarket 3 had the highest sales and Location [tier 2] had the highest sales.
2. The grocery stores had the least sales.
3. Items with low fat content were more popular.

Machine Learning 
To make future prediction on the sales, the data was analysed as Supervised Learning.the training data contains all data variables while test data contains all the variables except the Item Outlet sales(target), which is to be predicted
Two regression models were compared : the Linear Regression and Decision Tree regression model. Based on the results of the two models; Decision tree regression model is recommended as its training data and test data R^2 values are closer(well balanced fit).

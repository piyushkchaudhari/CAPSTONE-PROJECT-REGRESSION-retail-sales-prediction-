# Retail Sales Prediction
### Retail Sales Prediction is a regression machine learning project. Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

## About dataset:
### This dataset contain information about over 3,000 drug stores in 7 European countries. the above Rossmann Stores dataset has 1017209 rows and 9 columns and store dataset has 1115 rows and 10 columns.

## Dataset
- Id - an Id that represents a (Store, Date) duple within the test set
- Store - a unique Id for each store
- Sales - the turnover for any given day (this is what you are predicting)
- Customers - the number of customers on a given day
- Open - an indicator for whether the store was open: 0 = closed, 1 = open
- StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed onpublic holidays and weekends. a = public holiday, b = Easter holiday, c =Christmas, 0 = None
- SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools
- StoreType - differentiates between 4 different store models: a, b, c, d
- Assortment - describes an assortment level: a = basic, b = extra, c = extended
- CompetitionDistance - distance in meters to the nearest competitor store
- CompetitionOpenSince[Month/Year] - gives the approximate year and month of the time the nearest competitor was opened
- Promo - indicates whether a store is running a promo on that day
- Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 =store is not participating, 1 = store is participating
- Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2
- PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

## Library Used
- Pandas : For loading the dataset and performing data wrangling
- NumPy : For performing data wrangling and math operation 
- Matplotlib: For data visualization.
- Seaborn: For data visualization.
- Missingno : For Num Values visualization. 
- Sklearn: For Machine Learning Models.
- Statsmodels: For variance inflation factor

## Steps involved
- Installing libraies and getting the dataset.
- Performing EDA (exploratory data analysis).
- Drawing conclusions from the data.
- Preprocessing the data.
- Feature Engineering
- Handling Multicollinearity
- Lable Encoding for categorical data 
- HYPERPARAMETER TUNING
- Training different models.
- Evaluating metrics of all the models.

## Algorithms used
- 1)LinearRegression
- 2)Lasso regression
- 3)Ridge regression
- 4)Elasticnet regression
- 5)Random Forest regression

## Conclusion
![image](https://user-images.githubusercontent.com/123857050/235145425-3e81f819-a49e-4a63-b927-b52a6e6db3b4.png)
-  Random forest model gives better results compared to other models
- random forest model gives 99% tranining accuracy and 98% testing accureacy
- random forest model gives less random mean squer error compare to other models.



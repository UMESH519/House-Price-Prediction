# New-Taipei-City-House-Price-Prediction
STAT 425 ( Applied Regression &amp; Design) Project. The Project was part of Stat 425 subject at UIUC where We were required to (in a group of 2-3) analyse Housing data by performing EDA, Modelling ( With Diagnostics) and provide interpretation of the results.


## Data Description:

The dataset is extracted from UCI Machine Learning Repository and it consists of a market historical dataset of real estate valuation collected from Sindian District, New Taipei City, Taiwan. The variables in the original dataset are :

X1 - Transaction Date
X2 - The House Age
X3 - The Distance to the nearest MRT station
X4 - The number of convenience stores in the living circle
X5 - The latitude
X5 - The longitude
Y - House Price per unit area

The ‘Transaction Date’ for example, is the date on which the house was sold. The house age is also one of the predictors that is used. This assumption is confirmed in our analysis. Variables Longitude and Latitude are the coordinates of the house in the locality.  For the analysis, we divided the dataset into train and test with a ratio of  70 is to 30. The seed is set at 7 to maintain reproducibility.

## Executive Summary
1) Through Extensive modelling on the dataset, We observed that from all the algorithms, Distance_MRT_Station was the most significant feature of the dataset. 
2) We also observed a positive association between No. of Convenience Stores and house price. 
3) For Modelling we removed Transaction Date from the analysis and replaced that with Transaction month. 
4) We also observed that there was significant increase in R-Square When we used a log-linear model in regression than a linear - linear model in regression
5) Though Random Forest gave the lowest error, It was the most difficult to tune due to the large number of parameters. Also it presented a more interpretable model.




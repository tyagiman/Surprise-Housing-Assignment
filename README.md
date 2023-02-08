# House Price Prediction

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## Problem statement
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

## Technologies Used
- Python 
- Pandas, Numpy, Seaborn
- Statsmodel, Scikit Learn, GridSearchCV
- Process: Exploratory data analysis, data cleaning, data transformation, model building, hyperparameter tuning

## Conclusions

- Foloowing are the top features with their coefficients based on Lasso regression
Neighborhood_NridgHt,0.602054 ; Neighborhood_NoRidge,0.595412 ; Neighborhood_StoneBr,0.330668 ; HouseStyle_1Story,0.311616; Neighborhood_Somerst,0.309355; Neighborhood_Crawfor,0.299277; GrLivArea,0.287606; Exterior2nd_ImStucc,0.223743; OverallQual,0.196574; Exterior1st_BrkFace,0.18317


## Acknowledgements
- This project was a part of Advanced Linear Regression Assignment by Bangalore IIITB & Liverpool John Morris University

## Contact
Created by Manish Tyagi

# Surprise-Housing-Assignment

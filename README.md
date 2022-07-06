# Advanced Regression Assignment - Surpirse Housing

This is to determine the predictor variables of Surprise Housing using advanced regression model, we are checking the features which are significant in predicting the price of a house, and How good those variables describe the price of a house.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
 
The company wants to know:
•	Which variables are significant in predicting the price of a house, and
•	How well those variables describe the price of a house.
 
Also, determine the optimal value of lambda for ridge and lasso regression

## Technologies Used

Python - version 3.7
Numpy - v1.21.5
sklearn - 0.24.2
Pandas - v1.3.5
Seaborn - v0.11.2

## Conclusions

I would prefer to go with Lasso Regression over Ridge Regression. 

- The values of R2 Score, RSS and MSE for Lasso Regression are slightly better value compared to Ridge Regression
- In Lasso Regression, we can push the model co-efficients to actual zero value. This means that the features which have co-efficent of 0 can be removed from the model. Hence this results in feature selection
- Complexity of the model also reduces, because we can remove the features with zero co-efficients
- The top most 10 predictor features are 
	OverallQual	
	LotArea	
	BedroomAbvGr
	GarageCars
	SaleType_Oth
	Fireplaces	
	OverallCond	
	BsmtFullBath
	Neighborhood_StoneBr
	Neighborhood_NoRidge

## Acknowledgements
Give credit here.

This project was inspired by UpGrad Learning platform in understaning Advanced Regression

## Contact
Created by [@Pranavi][https://github.com/pranavich/advanced-regression-surprisehousing.git] - feel free to contact me!

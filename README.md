# Data Analysis and Price Predict Report for Used Cars


## Introduction

In this report, we provided data analysis and price prediction model based on 426K used cars data. Conclusion is draw on the critical factors that impact car price and a car price prediction model is also recommanded. The purpose of the analysis is to help car dealership making informed decisions, optimizing operations, and delivering better value to customers.


In this application, you will explore a dataset from kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing.  Your goal is to understand what factors make a car more or less expensive.  As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.

## Business Understanding

The business objective is to understand the factors that impact used car prices. <br>
Data Problem Definition: 
* regression analysis to identify the key features that impact used car prices
* create a predictive model that estimates the market value of used cars based on the features identified above

### Conclusion on initial data analysis

* Based on correlation of the numeric columns, price has stronger relation with the age
* The manufacturer that has the most number of cars sold is Ford
* Car types that customers like the most are: seadan and SVU
* Car ages at 7,8,9,10 have the most sale
* Most of the cars for deal are automatic with gas

### Conclusion

The best model is the polynomial linear regression model with all features. From the later feature selection result, we can identify that features impact the price are: 
* fuel
* transmission
* cylinders
* age
* drive

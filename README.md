# Advance Regression Assignment
**Problem Statement**

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

1. Which variables are significant in predicting the price of a house, and

2. How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goal**

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [Dataset Understanding](#dataset-understanding)
* [Process Involved](#process-involved)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->
## Dataset Understanding 
- The data given ("train.csv") contains information about the sale of houses in Australia

- You can access the data definition which describes the meaning of the variables in data set from the file name "data_description"

## Process Involved
- Data Source and Data Definitions
- Data Understanding and Exploration
- Data cleaning
- Data preparation
- Model building and evaluation
- Observation and inference


## Technologies Used
- Python - version 3.6.9
- Numpy - version 1.21.5
- Pandas - version 1.3.5
- Seaborn - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
## Conclusion 
- The optimal lambda value in case of Ridge and Lasso is as below:
   - Ridge - 5
   - Lasso - 0.0005
- The Mean Squared error in case of Ridge and Lasso are:
   - Ridge - 0.01362
   - Lasso - 0.01341
- The Mean Squared Error of Lasso is slightly lower than that of Ridge
- Lasso helps in feature reduction as the coefficient value of one of the features became 0, hence Lasso has a better edge over Ridge.
- Based on Lasso, the factors that generally affect the price are the Living area square feet, Zoning classification, Overall quality and condition of the house, Foundation type of the house, Number of cars that can be accommodated in the garage, Total basement area in square feet and the Basement finished square feet area.
-Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price of a house.

## Acknowledgements
Give credit here.
- This is an assignment for Excutive PG diploma in ML and DL by IIIT Bangalore and Upgrad


## Contact
Created by
Harshal Bhatkar(harshalbhatkar10f98@gmail.com)

feel free to reach out to us!!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

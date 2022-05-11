# House Price Prediction_Advanced regression Assignment 
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Observations](#observations)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

 * Which variables are significant in predicting the price of a house, and

 * How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Observations:
* Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test,
* it is better to use Lasso, since it brings and assigns a zero value to insignificant features, enabling us to choose the predictive variables.
* It is always advisable to use simple yet robust model.
* Equation can be formulated using the features and coefficients obtained by Lasso

## Conclusions
#### Equation:
Log(Y) = C + 0.125(x1) + 0.112(x2) + 0.050(x3) + 0.042(x4) + 0.035(x5) + 0.034(x6) + 0.024(x7) + 0.015(x8) + 0.014(x9) + 0.010(x10)
+ 0.010(x11) + 0.005(x12) - 0.007(x13) - 0.007(x14) - 0.008(x15) - 0.095(x16) + Error term(RSS + alpha * (sum of absolute value of coefficients)
#### INFERENCE
* Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house.
* The higher values of positive coeeficients suggest a high sale value.
* The higher values of negative coeeficients suggest a decrease in sale value.
* When the market value of the property is lower than the Predicted Sale Price, its the time to buy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad.
- This project was based on Advance Regression.


## Contact
Created by Sachin Pawar - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

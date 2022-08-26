
# Car price prediction

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

Which variables are significant in predicting the price of a car How well those variables describe the price of a car Based on various market surveys, the consulting firm has gathered a large data set of different types of cars across the America market.


## Business Goal
We are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
## Acknowledgements

 - [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Automobile)
 - [Geely](https://en.wikipedia.org/wiki/Geely)
 


 


## Project Overview

A chinese car manufacturer Geely want to enter into American automobile manufacturing segment. But they arenot clear about the factors/ features affecting the price in the American segment, since all their vehicle manufacturing expertise was focussed on Asian markets.

The dataset from UCI ML repository consist of 26 different attributes. This project aims to find out which among them plays a crucial role in predicting the price of the car that in American auto industry. We used a linear regression model to predict the price of the car and acheived a r2 score corresponding to 88.39% and adjusted r2 score of 70.99%. Further the coefficients were regularized using a Ridge,Lasso regression and Elastic Net regression thereby improving the model performance. 

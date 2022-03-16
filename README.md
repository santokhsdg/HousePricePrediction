# House Price Prediction
>The case study aims at building a Regression model for predicting sale price of house from given
> set of features. The focus is to identify the most significant features to help business predict the actual value of the 
> prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Surprise Housing is company in real estate business in house purchase and sale.
- The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- Company wants to understand the pricing dynamics of a new Australian market.
- Study aims at to identify variables which are significant in predicting the price of a house.


### Assumption
- Multivariable Linear regression applicability over the use-case.

## Conclusions
- Subjective question have been added as pdf file.
- Lambdas Ridge: 10.06 , Lasso: 0.0051
- Model Selected: Ridge
- House Price Prediction Ridge LR Results and top 10 features:
    - | Training R2 | Test R2 |
      | ----------- |---------|
      | 0.81         |0.80    |

   | Features         | Coefficients|
   |------------| ----------- |
   | OverallQual      |	0.429866 |
   | GrLivArea        |	0.372071|
   | MSZoning_RM      |-0.163145|
   | BsmtFinType1_GLQ |	0.136721 |
   | BsmtCond_TA      |	0.096404 |
   | Condition2_PosN  |	-0.086746 |
   | CentralAir_Y     |	0.085344|
   | SaleType_New 	   |0.084409|
   | BsmtCond_Gd      |	0.067546 |
   | GarageQual_TA    |	0.065265|




## Technologies Used
- Pandas - version 1.2.4
- Numpy - version 1.20.1
- matplotlib - version 3.3.4
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit-learn  - version 0.24.1


## Contact
Created by [@santokhsdg] - feel free to contact me!

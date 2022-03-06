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
- Lambdas Ridge: 18.33 , Lasso: 0.0051
- Model Selected: Ridge
- House Price Prediction Ridge LR Results and top 5 features:
    - | Training R2 | Test R2 |
      | ----------- |---------|
      | 0.81         |0.80    |

   | Features             | Coefficients|
   |-------------| ----------- |
   | OverallQual          |	0.427518 |
   | GrLivArea            |	0.369334|
   | MSZoning_RM          |-0.161416|
   | BsmtFinType1_GLQ     |	0.137959 |
   | CentralAir_Y         |	0.087438 |
   | BsmtCond_TA            |	0.086049 |
   | Condition2_PosN |	-0.085530|
   | SaleType_New 	      |0.085428|
   | PoolArea           |	-0.073394  |
   | GarageQual_TA |	0.061064|


## Technologies Used
- Pandas - version 1.2.4
- Numpy - version 1.20.1
- matplotlib - version 3.3.4
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit-learn  - version 0.24.1


## Acknowledgements
Thanks to UpGrad Team and Tutors of IIITB for the guidance all the way through.


## Contact
Created by [@santokhsdg] - feel free to contact me!

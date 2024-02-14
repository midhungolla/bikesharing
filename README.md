# Boom Bikes Sharing Assignment
 A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to ongoin Covid-19 pandaemic. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes?
- How well those variables describe the bike demands?
- We are required to model the demand for shared bikes with the available independent variables. It will be used by business to understand demands vary with different features accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents
1. Genenral Information
2. Conclusions
3. Technologies used
4. Acknowledgements

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
- We have used day.csv as dataframe

## Conclusions
- The top 3 features contributing significantly towards explaining the demand of shared bikes are-
	- the temp with coefficient 0.5499
	- weathersit_Light Snow/Rain (weathersit = 3) with coefficient value -0.2880
	- year(yr) with a coefficient - 0.2331

- Interpretation and Suggestions-
	- Demand is more during Summer months(temperature is high)
	- The demand has significantly increased in the year 2019 as compared to 2018 as people must have become more aware towards saving the environment.
	- During light snow/rain/misty and spring seasons the demand goes down asthere is a negative correlation.

## Technologies Used
- pandas library - version 2.0.3
- numpy library - version 1.24.3
- matplotlib library - version 3.7.2
- seaborn library - version 0.12.2
- statsmodels - version 0.14.0
- sklearn - version 1.3.0

## Acknowledgements
- This project was based on Linear Regression Module for the Executive PG Programme in Machine Learning & AI

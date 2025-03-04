# BoomBikes - Bike Sharing Assignment

## **Problem Statement**

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands <br>

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

**Business Goal**:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Recommendations](#recommendations)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

**Objectives:**
The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions

- The equation of our best fitted line is as follows:
  - **_cnt_** = 0.08 + 0.24 x **_yr_** + 0.05 x **_workingday_** + 0.55 x **_temp_** - 0.18 x **_windspeed_** + 0.09 X **_Summer_** + 0.12 x **_Winter_** + 0.06 X **_Saturday_** + 0.09 X **_September_** - 0.07 X **_Moderate_**
- The linear regression model demonstrates strong generalization, as evidenced by the near-identical R² and Adjusted R² values for both the training (R²: 0.791 , Adjusted R²: 0.787) and test sets (R²: 0.756, Adjusted R²: 0.745). This close match indicates that the model has successfully avoided overfitting, suggesting it will likely maintain consistent performance when applied to new, unseen data.
- The highest coefficient values are observed in the three key feature variables— **temp(temperature)**, **yr(y**r)**, and **Winter** —indicating their significant impact.
- Factors influencing bike demand include **yr**, **workingday**, **temp**, , **windspeed**, **Summer**, **Winter**, **September**, and **Sunday**.

## Recommendations

- As per the model,temperature, year, and winter, as they have the biggest impact on bike demand.
- We can create special deals for summer and winter to attract more riders.
- Based on the weather conditions, give discounts or incentives when the weather is nice to encourage more bike rides.
- Make sure you have enough bikes available during busy times based on the important features.
- Use this model to understand bike demand in the American market and improve your business strategies.

## Technologies Used

- [Python](https://www.python.org/) - version 3.12.4
- [Matplotlib](https://matplotlib.org/) - version 3.8.4
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2
- [Statsmodels](https://www.statsmodels.org/stable/index.html) - version 0.14.2
- [Scikit-Learn](https://scikit-learn.org/stable/) - version 1.4.2

## Acknowledgements

- This project is a requirement for the Executive PG Programme in Machine Learning & AI offered by upGrad and IIIT Bangalore
- The inspiration for this project came from an upGrad live session on the industry relevance of linear regression models.
- The upGrad learning platform tutorials on linear regression served as a valuable resource for this project.

## Contact

Created by [@LavanyaKumarV](https://github.com/LavanyaKumarV)

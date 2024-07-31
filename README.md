# Project Name
This Assignment aims to empower a US bike-sharing provider Boombikes with insights to understand how exactly the demands vary with different features. They can accordingly enhance the business strategy to meet the demand levels, meet the customer's expectations and improve revenue.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Problem Statement:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. -In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know, Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.
Business Goal:
The business goal is to build a model which meets the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. Dataset:
The provided dataset has diffrent features that are affecting the demand of shared bikes. Through linear regresson model we have identified the independent features that are affecting the demand of shared bikes.

## Conclusions
Final Observations: As per the final model, the top 3 predictor variables that influences the bike booking are:

Temperature (temp): A coefficient value of ‘0.493534’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.493534 units.
Year (yr): A coefficient value of ‘0.234415’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.234415 units.
mnth_sept: A coefficient value of ‘0.073266’ indicated that a unit increase in mnth_sept variable increases the bike hire numbers by 0.073266 units.
So, it's suggested to consider these variables utmost importance while planning, to achive maximum Booking.

The next best features that can also be considered are,

windspeed: A coefficient value of ‘-0.151913’ indicated that a unit increase in windspeed variable decreases the bike hire numbers by 0.151913 units. The windspeed is negatively related to the output.
season_winter: A coefficient value of ‘0.079120’ indicated that a unit increase in season_winter variable increases the bike hire numbers by 0.079120 units.
weathersit_bad: A coefficient value of ‘-0.280719’ indicated that a unit increase in windspeed variable decreases the bike hire numbers by 0.280719 units.


## Technologies Used
Python 
Numpy
Pandas
Matplotlib
Seaborn
Statsmodels

## Acknowledgements
Upgrad, Blog


## Contact
Created by @yogbalaji - feel free to contact me!

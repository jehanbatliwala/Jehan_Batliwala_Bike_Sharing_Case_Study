# Project Name

> Bike Sharing Case Study using Multiple Linear Regression by Jehan F. Batliwala.

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A bike-sharing system allows individuals to rent bikes for short periods, either for a fee or free. Users can borrow a bike from a computer-controlled dock by providing payment information. BoomBikes, a US bike-sharing provider, faced revenue drops during the pandemic and aims to create a strategic plan to boost revenue post-lockdown. They want to understand the demand for shared bikes after the quarantine ends and have hired a consulting company to analyze significant variables affecting bike demand in the American market. They have collected a large dataset on daily bike demands based on various factors and surveys. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Variables that are significant in predicting the demand for shared bikes are as follows: `windspeed`,`weekday`,`mnth`,`workingday`,`yr`,`weathersit` and `holiday`.
- We can see that the equation of our best fitted line is:

cnt = 0.206 \times yr + 0.194 \times mnth - 0.120 \times holiday + 0.046 \times weekday + 0.033 \times workingday - 0.228 \times weathersit - 0.253 \times windspeed

- An R-squared score of 0.3999719805715999 is obtainted from the model, meaning that approximately 40% of the variance in the dependent variable is explained by the independent variables in your model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

Pandas: 1.5.3
Python: 3.10.9
Matplotlib: 3.7.0
Seaborn: 12.0b3
Sklearn: 0.24

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@jehanbatliwala] - feel free to contact me!

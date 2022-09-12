# Bike Sharing Case Study
This project shows EDA and multiple linear regression to predict the demand for shared bikes in the future.


## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Methods Used](#Methods-Used)
* [Conclusions](#conclusions)
* [Technologies Used](#Technologies-Used)
* [Language](#Language)
* [IDE](#IDE)
* [Files](#Files)
* [Acknowledgements](#acknowledgements)


## Problem Statement
US Bike-sharing trying to understand the demand for shared bikes after the Covid-19 which has caused a considereable dip in their revenues. The aim of this study is to create a Business Plan which could acceralte the profit after Covid-19 Pandemic.

The Company requirement is as follows -

* To identify the variables that are affecting the use boom bikes e.g. temp, humidity, windspeed, holiday etc.

* Create a linear model that can quantitavely relates to the usage of boom bikes

* Find out the accuracy of the model

## Methods Used

These are the steps used to understand, analyse, predict and present the information :

* Read the file, understand the data and visualize the data to see the behaviour (EDA, Exploraroty Data Analysis)
* Then the data will be split into trained and test data and train data will be rescalled
* The Training data will be used to train Data
* Residual Analysis will conducted
* Predict and evaluate on the split test set
* Formulate the equation

## Conclusions

* Top three of the main contributing features is as follows 
    * temp (Temperature) - with co-efficient of 0.4712
    * Light Snow (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) - with negative co-efficient of -0.3002
    * yr (Year) - with co-efficent of 0.2330
* From EDA it can be observed that 
    * Spring and winter has the low count of users, while summer and fall tend to be higher count of users
    * data shows 2019 there where more users than 2018, this could be due to the popularity increase with the product
    * Month data verifies the data accurated for Season as the season worsens the demand reduces
    * median on non holiday is higher than holiday, there is slight trend showing non holiday might be better trend
    * weekday data suggest there median are higher on mon-fri
    * workingday median shows that working day may be have a slight effect on use
 * Equation derived from the model can be represented as follows
 * 
#### Count  = 0.233 * yr - 0.1011 * holiday + 0.4712 * temp - 0.1107 * Spring + 0.0558 * Winter - 0.0688 * July + 0.0658 * September - 0.3002 * Light Snow - 0.0796 * Mist
* Dataset for this trail wasnt large enough so additional data provided in data will provide a more accurate model in the future.

## Technologies Used
* Pandas : 1.2.3
* numpy : 1.20.3
* matplotlib: 3.5.2
* seaborn : 0.11.2
* scikit-learn : 0.20.3
* statsmodels : 0.9.0

## Language
* Python

## IDE
* jupyter Notebook

## Files
* .pynb file -- jupyter file containing the code
* .pdf file -- subjective questions
* .csv file -- data set


## Acknowledgements
* [1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3


## Contact
Edwin Mathew 

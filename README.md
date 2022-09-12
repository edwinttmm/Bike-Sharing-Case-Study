# Bike Sharing Case Study
> Outline a brief description of your project.


## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Methods Used](#Methods-Used)
* [Conclusions](#conclusions)
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
Count  = 0.233 \times yr - 0.1011 \times holiday + 0.4712 \times temp - 0.1107 \times Spring + 0.0558 \times Winter - 0.0688 \times July + 0.0658 \times September - 0.3002 \times Light Snow - 0.0796 \times Mist

## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

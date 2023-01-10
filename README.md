# Bike_Sharing_System Case study
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.

> Organization want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    . Which variables are significant in predicting the demand for shared bikes.
    . How well those variables describe the bike demands



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Analysis Methodology
1. Data Sourcing
2. Cleaning Data
3. Exploratory Data Analysis
4. Model building with RFE
5. Calculate the evaluation metrics
6. Evaluate Regression model assumption

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The final factors affecting the demand for Bike sharing are:
[ 'Year', 'TempFeel', 'Windspeed', 'Season_Spring', 'Season_Winter', 'Month_Dec', 'Month_Jul', 'Month_Nov', 'WeatherSituation_LightSnow', 'WeatherSituation_Mist']
- The given r-squared value on training set indicates that 82.7% variability is explained by this model
- Also, the adjusted r-squared is: 82.3%
- Final equation can be written as:

0.24 + Year0.2428 + TempFeel*0.4551 + Windspeed(-0.0886) + Season_Spring(-0.1577) + Season_Winter*0.0835 + Month_Dec(-0.0783) + Month_Jul(-0.0662) + Month_Nov(-0.0926) + WeatherSituation_LightSnow(-0.2587) + WeatherSituation_Mist(-0.0817)

- TempFeel and Temp has high correlation with count variable
- TempFeel, Year and WeatherSituation_LightSnow has high impact on number of rentals


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - 1.21.5
- pandas - 1.4.2
- matplotlib - 3.5.1
- seaborn - 0.11.2
- python - 3.7

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Thanks to
- https://www.geeksforgeeks.org/
- https://pandas.pydata.org/
- https://seaborn.pydata.org/
- https://stackoverflow.com/


## Contributor
Created by 
- Satyanaraya D
> [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/dtsatyam) 

Please feel free to contact us.

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
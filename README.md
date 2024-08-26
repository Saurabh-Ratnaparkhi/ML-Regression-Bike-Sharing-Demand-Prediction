# Bike-Sharing-Demand-Prediction
## Problem Statement

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

![](https://github.com/Saurabh-Ratnaparkhi/ML-Regression-Bike-Sharing-Demand-Prediction/blob/main/Doc.png)


## Data Description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
## Attribute Information:
   • Date : year-month-day
   
   • Rented Bike count - Count of bikes rented at each hour
   
   • Hour - Hour of the day
   
   • Temperature-Temperature in Celsius
   
   • Humidity - %
   
   • Windspeed - m/s
   
   • Visibility - 10m
   
   • Dew point temperature - Celsius
   
   • Solar radiation - MJ/m2
   
   • Rainfall - mm
   
   • Snowfall - cm
   
   • Seasons - Winter, Spring, Summer, Autumn
   
   • Holiday - Holiday/No holiday
   
   • Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

## 📖 EDA Observations and findings

* From Exploratory Data Analysis, we found that the bike rentals follow an hourly trend
where it hits the first peak in the morning and the highest peak next, in the evening.
* It was also found that these trends are prominent only during weekdays and working days, leading us to make a safe assumption that office-goers make a notable contribution in bike sharing demand. 
* In addition, seasons were observed to have a notable effect on bike rentals, seeing high traffic during the summers and a significant
low during the winters.

## 📖 Implementation of models and evaluation Metrics
As the data available is collected only over the period of one year, time-series forecasting is not considered. But instead, traditional regressive Machine Learning Models are trained and evaluated
  * Linear Regression 
  * Lasso Regression 
  * Decision Tree

The top models are picked to tune hyperparameters in order to further optimize their results.

The metrics measured for evaluating performance of bike share prediction models are:
  * MSE
  * RMSE
  * MAE
  * R-SQUARED, and
  * Adjusted R-SQUARED

## 📖 Results

# Regression-Capstone-Seoul-Bike-Sharing-Capstone-Project

### Introduction
Seoul is the captial of South Korea. This city has a population of more than 10 million. Having this much population in one city, commuting from one point to another can often becomes a challenging task. Here is where rental bike sharing comes to the rescue as it offers rental bikes at different locations of the city to make commuting more accessible and convinent to the public. But often time the demand of these rental bikes differ. They differ with respect to seasons, hour of the day, the temperature, humidity, wind speed and other weather condition. If we are able to predict the demand of these rental bikes before hand, we can reduce the cost of operations and therefore improve the availability of these bikes when required.

So in this project we perform Statistical modelling to analysis what weather factors that are affecting the demand of rental bikes.

### Dataset Description
The data is given in per hour basis. Following are the columns provided to perform modelling and prediction:

Date: - Date of the year,
Rented Bike Count: - Number of bikes rented,
Hour: - Hour the day,
Temperature(°C): Temperature in that particular hour of the day,
Humidity(%): - Humidity in that particular hour of the day,
Wind speed (m/s): - Wind speed in that particular hour of the day,
Visibility (10m): - Distance visible from the naked eye,
Dew point temperature(°C): - Temperature at which first drop of water condenses,
Solar Radiation (MJ/m2): - Amount of solar radiation in that hour,
Rainfall (mm): - Amount of rainfall in that hour,
Snowfall (cm): - Amount of snowfall in thar hour,
Seasons: - Season of the year,
Holiday: - If there is any festive holiday,
Functioning Day: - If the rental bike was functioning or not

### Some Inferences after modelling
It comes to my finding that the most important feature in the prediction of rental bike demand is the Temperature parameter. Also we learn that people tend rent bikes during 18th hour of the day. This is when the temperature just starts to drop after reaching its peak in the 17th hour. Also people use rental bike service during Summer season the most, followed by Autumn and Spring. People use it the leat in winter season. Also we learn form other parameters that people tend rent bikes when there is less wind speed(around 1 m/s), almost no rainfall and snowfall, 40 to 50 % humidity and higher visibility.

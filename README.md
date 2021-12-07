### World_Weather_Analysis

#### Project Overview
Use openweathermap api to collect weather data for the 2000 cities and use the googlemaps api to plan the travel. 


### Tools Used: 
python, googlemapsapi, openweathermapapi

### Procedure: 
Use numpy library to randomly generate 2000 lattitude and longitute combination. Find the closet city to those 2000 lattitude and longitude with the help of the citipy library. Now with the names of the 2000 cities use openweathermap api to get information like temperature and humidity. Use the data collected to narrow down the city with the desired tempreature range. From the list choose four location to travel and use googlemaps api to show the directional map. 



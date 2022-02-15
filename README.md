# World Weather Analysis

Python Using APIs 
## Overview of Analysis
The purpose of World Weather Analysis is to find potential lists of travel destinations and find nearby hotels in those cities. Then pick 4 cities and create travel itinerary.  

## Tools Used
* Python pandas,numpy, matplotlib 

## Process
Following steps were taken 
* Weather Database : 
    * Create random list of latitudes and longitude
    * Find the nearest city for each lattitude and longitude using citypy .
    * Retrieve Weather Data using API call with the OpenWeatherMap. https://openweathermap.org/api
    * The data retrived from OpenWeatherMap JSON is parsed and saved on WeatherPy_Database.

* Vacation Search: 
    * Using the Weather database created on above steps, the cities that meets user enter minimum and maximum temperture criteria were filtered. Then, Google API was used to find the hotel in each of those cities.  
    https://console.developers.google.com
    * Cities without hotels were removed and displayed on google maps  

* Vacation Itinary:
    * Using the Vacation hotels, 4 cities were picked within the United States, created the driving route and displayed on map. 

## Summary
   The analysis can reused to plan for trip by scouring vacation destinations and picking final 4 cities for the trip. It can be tweaked to serch vacation spots within certain part of the World by changing latitude and longitude list. 




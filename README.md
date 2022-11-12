# World_Weather_Analysis

## Overview
For this challenge, I was tasked with using Python to enhance a travel app by adding weather data. Users of the app can filter the data for their weather preferences, which will identify potential travel destinations and nearby hotels. 

### Resources
 * Data Source: cities around the world selected from randomly-generated coordinates
 * OpenWeatherMap API
 * Google Directions API
 * Software: Python 3.7.1, Jupyter Notebook 

## Deliverable 1: Retrieve Weather Data
I created a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with OpenWeatherMap. I retrieved weather data for each city and placed them in a data frame. 

### Results
A sample of the data frame with randomly-generated cities and their associated weather data 
![WeatherData](https://github.com/CSoldo1/World_Weather_Analysis/blob/main/Deliverable1.PNG)

## Deliverable 2: Create a Customer Travel Destinations Map
For this part of app development, customeers could input their weather preferences. These preferences would identify travel potential travel destinations and nearby hotels. These destinations were added to a map with pop-up markers that displayed relevant information about each city. 

### Results
The marker layer map shows weather and hotel information for cities within the traveler's weather preference. 
![Marker Layer Map](https://github.com/CSoldo1/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)

## Deliverable 3: Create a Travel Itinerary Map
I used the Google Directions API to create a travel itinerary that showed the route between four cities chosen from the customer's possible travel destinations. I then created a marker layer map with a pop-up marker for each city on the itinerary. 

### Results

![WeatherPy Travel Map]()

![WeatherPy Travel Map Markers]()




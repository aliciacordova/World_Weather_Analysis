# World_Weather_Analysis


## Overview
This challenge consists on test PlanMyTrip app. First retrieving weather data including the weather description cities across the world. Second create a costumer travel destination map with their weather preferences and filter data accordingly. And third identifies potential travel destinations, nearby hotels and creates a travel itinarary map using the Google Maps Directions API. 

## STEP #1 Retrieve Weather Data

We had to retrieved 2000 sets of coordinates (latitude and longitude) through a request to the OpenWeatherMap API to get the cities.

![image](https://user-images.githubusercontent.com/87447639/134591329-75647e35-5ee5-4a26-a672-bbd3f1715bc4.png)

![image](https://user-images.githubusercontent.com/87447639/134589525-2cc9c335-b084-4293-8b48-c17ecb189ddd.png)


## STEP # 2 Create a Customer Travel Destinations Map

To create the travel destination we choose a minimum and maximum temperature for this trip. 

![image](https://user-images.githubusercontent.com/87447639/134590115-ed52dc12-50c9-47d9-929d-369db2a38cea.png)

We get all the cities available with these conditions. 

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/87447639/134589328-e6ad44b5-91b6-4a04-9650-c26328a00888.PNG)


## STEP #3 Create a Travel Itinerary Map

We create a travel itinerary that suggest 4 cities in USA that can be visited, with hotel accommodations, and have amazing sightseeing.

![image](https://user-images.githubusercontent.com/87447639/134589704-a742cd48-74f7-4fad-80a2-358e2b36ade1.png)


![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/87447639/134589369-2077396f-8bf6-4d88-88bb-b059a446f0ce.PNG)

![WeatherPy_travel_map](https://user-images.githubusercontent.com/87447639/134590463-804a393b-40b4-4095-8640-d94ae6620e47.PNG)

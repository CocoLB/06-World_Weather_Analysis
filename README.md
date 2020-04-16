# World_Weather_Analysis

## Project Overview
We've been tasked by PlanMyTrip, a travel technology company, to collect and present data obtained from the website search page in order to find the ideal hotels in the world based on weather criteria.

## Resources
- Python 3.7.6, Anaconda 4.8.3, Jupyter Notebook-Gmap, Python Requests, JSON Traversals
- Pandas Library, CitiPy, NumPy, SciPy, Matplotlib
- APIs (OpenWeather, Gmap) 

## Summary
- Using NumPy module, we generated a list of 1,500 random latitudes and longitudes, which made a list of more than 500 cities, using CitiPy. We then used the Open Weather API, and parsed the JSON data to get the weather for each of them.

<img src="Weather_Data/city_data.png" width="350">

- We created scatter plots to visualize the relation between latitude and temperature/humidity/cloudiness/wind speed.

<img src="Weather_Data/Fig1.png" width="200"><img src="Weather_Data/Fig2.png" width="200"><img src="Weather_Data/Fig3.png" width="200"><img src="Weather_Data/Fig4.png" width="200">

- We created creating linear regression graphs to determine the correlations between latitude and the same weather data

<img src="Weather_Data/linearNHtemp.png" width="200"><img src="Weather_Data/linearSHtemp.png" width="200"><img src="Weather_Data/linearNHhumidity.png" width="200"><img src="Weather_Data/linearSHhumidity.png" width="200">

- We createds heat maps, using Google Maps/Places API showcasing the same correlations

<img src="Weather_Data/temperature heatmap.png" width="200"><img src="Weather_Data/humidity heatmap.png" width="200"><img src="Weather_Data/cloudiness heatmap.png" width="200"><img src="Weather_Data/cloudiness heatmap.png" width="200">

- After we filtered our lict of cities by the customer's preferred min and max temperatures, we found a hotel nearby each location using Goodle Maps/Places API and Search Nearby fetaures, and created a heat map displaying info about the city, current temperature and hotel name.
<img src="Weather_Data/hotel heat map.png" width="350">







# Python-API
Python script that visualizes the weather of 500+ cities across the world of varying distance from the equator

Following scatter plots showcase the following relationships:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

Notebook:
Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.
Performs a weather check on each of the cities using a series of successive API calls.
Includes a print log of each city as it's being processed with the city number and city name.
Saves both a CSV of all data retrieved and png images for each scatter plot.

My Findings:
1. The closer a city is located to 0 in latitude, the higher the temperature will be. 
        #City Latitude vs. Temperature
    
2. There is no relation between a city's geographic location and its percentage of cloudiness. 
        #City Latitude vs. Cloudiness
    
3. A slight concentration in high humidity percentage and a higher number of latitude.
        #City Latitude vs. Humidity

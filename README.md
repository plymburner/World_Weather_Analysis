# World_Weather_Analysis
World Weather Analysis assignment

## Overview of the Analysis

    The purpose of this project is to utilize API connections in the analyis to provide ancillary data that otherwise would not be available in a standard dataset due to size (i.e. Google Maps Geolocational data) or dynamically changing data (i.e. OpenWeatherMap). Using this sources boost the availability of data and preset opportunities to add more layers to evaluate the data and present the information adequately for the purposes of the broadening and deepening an analysis project.

## Results
    1. Deliverable 1: Weather_Database
        a. I was able to create 2,000 random coordinates for evaluation in the city weather analysis
        b. Of the 2,000 random coordinates, 759 cities were found
        c. The weather data for these cities were successfully pulled and saved to the WeatherPy_Database.csv
    2. Deliverable 2: Vacation Search
        a. Utilized the Min/Max Temperatures to limit the number of Vacation Locations and saved the data to a new dataframe
        b. Enhanced the dataframe with an additional column with a hotel name in the immediate vacinity of the coordinates
        c. Created a layer map with the information provided
        https://github.com/plymburner/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png
    3. Deliverable 3: Vacation Itinerary
        a. Created individual dataframes for the destinations with their associated coordinates
        b. Included the directions layer in the report, including tags for the cities
        https://github.com/plymburner/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png
    

# PlanMyTrip Vacation_Itinerary
Module 6, Python APIs - UNCCH Data Analytics Bootcamp, Spring 2023

## Project Overview

### Purpose
This exercise was performed to enhange the PlanMyTrip app, identifying hotels and driving routes for vacation itineraries using nearby cities as inputs. A beta tester will input 4 cities from a list of destinations, and the aim is to generate a travel route between them complete with a map output. 

## Method
 Using Python, and several libraries, in the Jupyter Notebook environment, I generated random worldwide latitude and longitude values, then used OpenWeatherMap to generate weather data for nearyby cities, which was output to a CSV file. Next, the CSV file was read into a new notebook which used the city data to create a travel destinations map using GeoApify. From there, a possible driving route looped between 4 cities was generated using GeoViews. 

 ## Resources
- Data Sources: randomly generated
- Software: Python 3.10.5
- IDE: Jupyter Notebooks

## Results
- Data Outputs: 
    [Weather Data](/Weather_Database/WeatherPy_Database.csv)
    [Vacation Data](/Vacation_Search/WeatherPy_vacation.csv)

- Ridesharing summary DataFrame by city type:
    ![World Destination Map](/Vacation_Search/WeatherPy_vacation_map.png)
    ![Travel Route Map](/Vacation_Itinerary/WeatherPy_travel_map.png)

## Summary
The software performed well for the beta test, and can be approved for further testing and implementation.
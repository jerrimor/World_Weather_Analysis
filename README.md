# World_Weather_Analysis

## Overview
The purpose of this project was to create an application that would utilize the input from an individual who is interested in traveling and provide weather data about their potential destination/s.  API calls are used to capture weather information from Open Weather Map and returned in a JSON format so that it can be parsed. Open Weather Map returns weather information for the locations provided, once the latitude and longitude details are sent.  Also, within this project, API calls are built and sent to Google Maps to output maps for the user to see potential destination spots and to view hotel information in the area.  The map shows markers for the cities of interest. All of this information gathered was brought in by API calls, in JSON format, then DataFrames were created to hold the information.  These details about vacation destinations are to assist potential travelers with choosing cities to visit based on the climates of these cities. 

## Summary
Weather and hotel information is provided for random lat/long and in the last project of this challenge, the user inputs their requested temperatures for the trip.  Once the temperatures are selected, the queries are also limited in city selection by these temperature limits.  Once the markers are displayed on the map(as seen below), it is evident that the traveler suggestions will be limited to a few continents, based on the time of year.  A final map (seen below) is shared with the travelers that has the route of a potential vacation outlined within the map. 


![C46DBB76-BD0D-4540-9AEB-0FA9248D3F48](https://user-images.githubusercontent.com/96222437/152709213-85eadac6-0664-48b7-95ed-f74f141d4599.jpeg)

![WeatherPy_travel_map](https://user-images.githubusercontent.com/96222437/152709058-d56187ce-fcc8-4ee5-81fb-0c86a4b739e3.png)



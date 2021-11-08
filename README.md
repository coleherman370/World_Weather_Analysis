# World_Weather_Analysis

## Project Overview
Use APIs to retrieve data about various locations to identify potential vacation destination based upon input criteria. 

## Resources
* Data Source: city_data.csv; ride_data.csv
* Software: Python 3.9.6, Visual Studio Code 1.61.1
* Google Map APIs

## Summary
The various scripts submitted produce a series of random Lat and Long coordinates. The nearest cities are then retrieved for those coordinates. Once associated to cities, those cities are submitted to Google via api where information such as Max Temp and Current Weather is retrieved. The user is then asked for a desired temperature range they wish to vacation in. The script then presents them a map of the random cities that fit within that temperature range.
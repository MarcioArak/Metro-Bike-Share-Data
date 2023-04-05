# Metro Bike Share Data

## Overview 
Part of the LA County Vision 0 Project. Vision Zero is a strategy to eliminate all traffic fatalities and severe injuries, while increasing safe, healthy, equitable mobility for all. First implemented in Sweden in the 1990s, Vision Zero has proved successful across Europe — and now it’s gaining momentum in major American cities.

The software makes use of Metro Bike Share Real time data to display a map that will be referred to as Metro Bike Share Real Time (MBSRT). This map will fetch geojson data from the Metro’s Bike Share web app, and display a marker, representing a station, using Google’s Map API. From there the user will be able to interact with numerous built in features, such as filtering, directions, heatmaps, etc. Currently the purpose of our software is to help users around the greater Los Angeles area to obtain a bike, and cycle around the city using the safest way possible. Ideally contributing to our ultimate goal of realizing Vision Zero.

## Metro Bike Share Data Web App
The application shows information on metro bike stations around LA. The application displays each stations name and number and each station has a color and size appointed to them, color represents which day was the busiest and the size represents the total amount of trips the station had.

When clicking on station a window will display:
* Status: Active or Inactive
* Graph of average amount of trips by day
* Peak hours of usage by day
* Peak day of originating trips
* Visuals for certains stats

You can also filter the stations by day. This will change the stations size and color to represent something different. Color will now mean which hour is the busiest instead of which day is the busiest and size will be the number of trips during the selected day instead of total number of trips.

When clicking on the filtered stations the window will display:
* Status
* Graph of average trips per hour
* Peak hour of day
* Average amount of trips of that day

## Technologies Used
* Google's Map API
* Google Sheets
* ArcGIS API
* Javascript, Javascript API, HTML and CSS

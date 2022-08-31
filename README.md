# World_Weather_Analysis
## Overview:
This analysis looks at different weather data patterns around cities worldwide and offers insights based on clients' weather preferences. I created a Pandas DataFrame with over 500 of the world's unique cities and their weather data in real time. My analysis contains over 1,500 random latitudes and longitudes, each including specific weather data for each location. I then created scatterplots of the weather data, determined the correlations, and created a series of heatmaps using the Google Maps and Places API.

### The DataFrame includes the following weather characteristics:
- City, county, and date.
- Latitude and longitude.
- Maximum Temperature.
- Humidity.
- Cloudiness.
- Wind speed. 

## Visualize the Weather Data:
I created a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. This tool can be useful for clients' to visualize their weather preferences when booking hotels, trips, and forming itineraries. 

## Map Your Vacation!
Once the customers have filtered the database (DataFrame) based on their temperature preferences, they can select certain cities and view a heatmap! The heatmap can help individuals view the maximum temperatures prevalent in their selected cities. In addition, clients' can also place a marker on each city selected which will provide them with a country code, maximum temperature, and name of a nearby hotel within three miles of the coordinates when the marker is clicked. 

## Here's a sample of a potential search opption: 
<img width="1206" alt="Screen Shot 2022-08-31 at 5 17 15 PM" src="https://user-images.githubusercontent.com/104043438/187801277-7b79f4d1-999d-419b-a175-bd76b2343bc1.png">

### After implementing a clients' preferences: 
- A pop-up marker appears and displays information based on the specific location. Summarizing the area's max temperature, location, and weather description. This is just one of many tools my analysis offers. 

# Python-API-Challenge

![nasa-gyp1xkjZNg8-unsplash](https://github.com/ryodaimatsui/python-api-challenge/assets/137141385/dbb2c068-8b0b-4466-b30c-bd4b3ea0edf8)

This challenge begins by generating random geographic coordinates and taking these coordinates to generate a list of cities using the citiypy library. Following this, the OpenWeatherMap API is utilized to request weather data for the list of citites. The dataframe that is created using this data includes the following columns:
- [City, Latitude, Longitude, Max Temperature, Humidity, Cloudiness, Wind Speed, Country, Date]

From this dataframe, four scatterplots are created looking at the relationship between the city latitude and : 1) max temperature; 2) humidity; 3) cloudiness; 4) wind speed. The same sets of relationship are measured and plotted on linear regression plots for the cities that are located in the northern and southern hemispheres.

For the second part of the challenge, the csv file containing the weather data gathered from the previous part of the challenge is read in and framed. This dataframe is filtered according to my ideal weather conditions. Subsequently, the GeoApify API is utilized to request the nearest hotel for the each city in the filtered dataframe. Whether a hotel is found in a particular city or not, the city is nevertheless included in the final map.

# API-Challenge

**Section I - WeatherPy**

In this project, you will develop a Python script to illustrate the weather conditions of over 500 cities across the globe located at varying distances from the equator. To accomplish this, you will use a simple Python library, the OpenWeatherMap API, and some common sense to construct a model that represents the weather conditions across cities worldwide.

You will generate a series of scatter plots to demonstrate the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Additionally, you will perform linear regression analysis on each relationship. This time, however, you will separate them into two categories: the Northern Hemisphere (latitude greater than or equal to 0 degrees) and the Southern Hemisphere (latitude less than 0 degrees).

The linear regression analysis will be performed on the following relationships:

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

In order to accomplish these tasks, you will randomly select at least 500 unique (non-repeating) cities based on latitude and longitude. Subsequently, you will conduct a weather check on each city utilizing a sequence of successive API calls. You will also maintain a print log of each city as it is being processed, displaying the city number and name.

**Section II - VacationPy**

In the second part of this project, first step of this task involves creating a map that showcases a point for every city present in the city_data_df DataFrame. The size of each point must be proportional to the humidity level recorded for each city.

Then, we need to narrow down the `city_data_df` DataFrame to find your ideal weather condition and create a new dataframe.

After creating new dataframe, for each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.

Lastly, add the hotel name and the country as additional information in the hover message for each city in the map.

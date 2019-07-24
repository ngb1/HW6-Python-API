# HW6-Python-API

## WeatherPy

In this example, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I used a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

My objective was to build a series of scatter plots to showcase the following relationships:


Temperature (degC) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (m/s) vs. Latitude


My final notebook:


- Randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude.
- Performed a weather check on each of the cities using a series of successive API calls.
- Included a print log of each city as it's being processed with the city number and city name.
- Saved both a CSV of all data retrieved and png images for each scatter plot.


As final considerations:


I completed the analysis using a Jupyter notebook.
I used the Matplotlib or Pandas plotting libraries.
I included a written description of three observable trends based on the data.
I used proper labeling of your plots, including aspects like: Plot Titles (with date of analysis) and Axes Labels.


## Conclusions

After completing the WeatherPy data analysis I could determine the following trends below:

-More data points in northern hemisphere (positive latitudes) is in agreement with geography and population distribution (and number of cities) in the world.
-Maximum temperatures are higher between latitude 0 and 40 during the arctic summer (austral winter), and temperatures tend to be lower at latitude -60 and 80 (closer to the poles). 
-Humidity is higher around the equator (latitude 0) at this time of the year, there are lower humidity values at latitudes -20 and 40, probably due to mountain chains in these locations.
-Fewer cloudiness points between 40 and 70%, meaning that this time of the year most cities are either very cloudy or clear of clouds. No clear pattern was obtained at latitude level.
-Wind speed higher than 10 m/s at latitudes -40, 10 an 70, most cities have wind velocities below 6 m/s.


## Authors

* **Nicolas Gomez Bustamante** - *Initial work* - [PurpleBooth](https://github.com/nbg1)


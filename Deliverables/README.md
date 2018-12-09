'''––––––––––––––––––––––––––– * Analysis * –––––––––––––––––––––––––––
1) The weather tends to increase as it nears the equator, and this can be expected.
   However, the northern hemisphere is currently warmer than the south, and seems to peak
   in proximity to ~30˚ N Latitude.
2) Humidity tends to be much higher near the equator, with most cities
   within 20˚ north or south having levels above 60%.
3) Geolocation seems to have little influence on cloudiness or windspeed.
4) Humidity tends to increase as the north and south pole are approached.
'''
'''
Tasked with building a representative model of city weather based on geolocation;
Will utilize OpenWeatherMap(API) & Citipy to develop model.

Requirements:
    1) randomly select 500 cities based on lat/long coordinates,
    2) perform API calls on OpenWeatherMap to collect weather information per city,
    3) print log of a) city being processed, b) city number, & c) city name,
    4) Create scatterplots of:
            Temperature (F) vs. Latitude
            Humidity (%) vs. Latitude
            Cloudiness (%) vs. Latitude
            Wind Speed (mph) vs. Latitude
    4) output data to csv & save scatterplots to png,
    5) write up description of 3 obesrvable trends based on the data.
'''

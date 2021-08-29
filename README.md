# python-api-challenge

## WeatherPy
I write a script that evaluates the weather in 500+ cities around the world to determine if their proximity to the equator affects weather conditions, namely max temperature, humidity, cloudiness, wind speed.

#### Observing Weather Conditions Near the Equator
As expected, temperature increased as one nears the equator. This mostly due to Earth's rotation causing a bulge towards the middle, thereby being closer to the Sun. But since the equator is an imaginary line, the "real" equator, i.e., where it's hottest, is between 0° and 20°.

The other observed weather patterns (humidity, cloudiness, wind speed) do not appear to be affected by proximity to the equator. Even when the results were split between the hemispheres, there was no significant difference that would suggest correlation.

The limitations of the other data is they do not account for historical weather data - only current data. Weather patterns are complex and cyclical. If the observed data doesn't reflect different seasons, one might reach the wrong conclusions, especially regarding humidity, cloudiness, and wind speed.

The following scatter plots show the observed data.

[Scatter 1](output_data/plot_temp.png)

[Scatter 2](output_data/plot_humid.png)

[Scatter 3](output_data/plot_cloud.png)

[Scatter 4](output_data/plot_wind.png)


## VacationPy
I narrow the results from WeatherPy to cities that have "ideal" weather conditions (less than 10 mph winds, temperatures in the 70s, and no clouds) and plot the nearest hotel results on a heat map that shows humidity.

#### Now Boarding for The Mediterranean
After running the code, turns out The Mediterranean area is the perfect vacation spot. Who doesn't love pasta and gyros?!
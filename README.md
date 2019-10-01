# WeatherAPI

I wanted to determine if lattitude had an impact on average weather (temperature, humidity, cloiudiness, wind speed). Data was gathered from openweathermapy. 500+ cities. The cities are selected randomly using citipy and random lattitude-longitude cooridants. Pandas and matplotlib are used to manipulate data and generate dataframes in addition to producing plots that visually summarize the findings.

![LatitudevsLongitude](output_data/LatitudevsLongitude.png)

In general, the closer one is to the equator the higher the maximum temperate in a given year. Our expectation is the maximum temperature plotted by latitude would follow a concaved parabola. This confirmed in the Latitude vs Temperature plot
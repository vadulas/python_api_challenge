
# H3 The Jupyter notebooks has scripts to analyse the whether in various citites across the globe and picks the cities for vacationing based on the set preference of temperature, cloudiness and wind speed.

**Following are the scripts**

**1.WhetherPy.ipynb - Following are the plots that have been created for the the analysis**
Scater Plots: 
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude


Plots to determine the linear regression on each relationship:
- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

**2.VacationPy.ipynb Narrows down the DataFrame to find the ideal weather condition based on the following criteria**


- A max temperature lower than 86 degrees but higher than 75
- Wind speed less than 10 mph
- Zero cloudiness

Using Google Places API finds the first hotel for each city located within 5000 meters based on the above criteria and plotes them on the Map with the markers.







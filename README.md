# python-api-challenge
## WeatherPy Task:
-Utilize the citipy library in Python to generate a list of 500+ random, non-repeating cities.
-Iterate through this list and call the OpenWeatherMap API to obtain maximum temperature, humidity, cloudiness, and wind speed.
-Create a series of scatter plots, to show the relationships between:
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Temperature (F) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Humidity (%) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloudiness (%) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Wind Speed (mph) vs. Latitude
-Then create a linear regreesion to show the correlation between:
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Northern Hemisphere - Temperature (F) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Southern Hemisphere - Temperature (F) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Northern Hemisphere - Humidity (%) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Southern Hemisphere - Humidity (%) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Northern Hemisphere - Cloudiness (%) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Southern Hemisphere - Cloudiness (%) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Northern Hemisphere - Wind Speed (mph) vs. Latitude
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Southern Hemisphere - Wind Speed (mph) vs. Latitude
<br/>The dataframe created of the weather data should be exported as CSV to use in the next part.
## VacationPy Task:
-Create a heat map that displays the humidity for every city from WeatherPy.
![image](https://user-images.githubusercontent.com/84332100/127257503-eaa599c2-3377-44b8-8920-ef64a5cc1661.png)
-Narrow down the data. The following parameters were used:
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A max temperature lower than 85 degrees but higher than 65.
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Wind speed less than 10 mph.
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloudiness less than 30%.
-Use Google Places API to find the first hotel for each city located within 5000 meters of coordinates.
-Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
![image](https://user-images.githubusercontent.com/84332100/127257534-1ab97b3e-cdbf-4697-a679-76af636501a8.png)

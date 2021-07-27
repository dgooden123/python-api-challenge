# python-api-challenge
WeatherPy creates a eries of scatter plots to display the relationship among 647 random cities between:

Temperature (C) vs. Latitude (Figure 1)
Humidity (%) vs. Latitude (Figure 2)
Cloudiness (%) vs. Latitude (Figure 3)
Wind Speed  vs. Latitude (Figure 4)

Observations: Not surprisingly, the cities with a latitude closest to zero have the highest maximum temperature. The linear regression further demonstrates this relationship by hemisphere. The scatter plots and the linear regression showed that wind speeds decreased as cities moved further from the equator. 


Linear regression by hemisphere examining relationship between latitude and weather element
Northern Hemisphere - Temperature (C) vs. Latitude (Figure 5)
Southern Hemisphere - Temperature (C) vs. Latitude( Figure 6)
Northern Hemisphere - Humidity (%) vs. Latitude (Figure 7)
Southern Hemisphere - Humidity (%) vs. Latitude (Figure 8)
Northern Hemisphere - Cloudiness (%) vs. Latitude (Figure 9)
Southern Hemisphere - Cloudiness (%) vs. Latitude (Figure 10)
Northern Hemisphere - Wind Speed  vs. Latitude (Figure 11)
Southern Hemisphere - Wind Speed  vs. Latitude (Figure 12)

Using the random cities and gmap, VactionPy creates a heat map using latitude, longitude, and humidity. 
Then it finds hotels within 5,000 meters of the perfect weather condition (max temp 25-28 degrees C, wind less than 10, and no cloudiness) 
The final heat map shows the locations of the hotels

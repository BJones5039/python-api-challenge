# python-api-challenge

Explore weather trends and plan future vacations with WeatherPy and VacationPy.

**WeatherPy**

Objective: Investigate weather patterns around the equator using Python, APIs, and data visualizations.

Data Collection:

Utilize OpenWeatherMap API and citipy Python library.
Generate random coordinates and find the nearest city.
Plots:

Create scatter plots for:
Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude
Linear Regression:

Compute linear regression for each relationship.
Separate plots into Northern and Southern Hemispheres.
Interpret the models and note any relationships.

**VacationPy**

Objective: Plan vacations using weather data, Jupyter notebooks, geoViews, and the Geoapify API.

Map Visualization:

Create a map with points for each city, where point size represents humidity.
Ideal Weather Conditions:

Narrow down cities based on specified weather conditions.
Adjust specifications for practical API requests.
Hotel Information:

Create hotel_df DataFrame to store city, country, coordinates, and humidity.
Use Geoapify API to find the first hotel within 10,000 meters for each city.
Map Enhancement:

Add hotel name and country to the hover message for each city on the map.

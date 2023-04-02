# python-api-challenge
Python API and JSON request challenge

Background
Using Data's true power to definitively answer the question, "What is the weather like as we approach the equator?".

WeatherPy
1. A python script is will be used to visualise the weather of over 500 cities of varying distances from the equator.
2. Using citipy Python library to get the closest cities from the random generated gepgraphic coordinates.
3. Using the OpenWeatherMap API to retrieve weather data from the cities list.
4. Create scatter plots for 4 different relationships 
5. Separate plots into Northern and Southern hemisphere and calculate the linear regression for each relationship.
6. Store dataframe into csv files and scatter plots into png files

VacationPy
1. Using the same csv files store from WeatherPy challenge (for weather and coordinates) to create a map visualisation
2. First map visualisation involes diplaying points for each city, with size of each point dependent on the humidity of the city.
3. Create dataframe for my ideal weather condition (max temp range 10C - 25C and humidity between 50-70%).
4. Using Geoapify API to find nearest hotel (to 10,000 meters) of each city coordinates.
5. Second map visualisation involves displaying all points for each city, with hover message to include nearest hotel name and country.


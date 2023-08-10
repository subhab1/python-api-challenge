# python-api-challenge
# Background
This project has been divided into two parts, WeatherPy and VacationPy. In WeatherPy, we are required to create visualization of the weather of over 500 cities at varying distances from the equator. The citipy library, and the OpenWeatherMap API were used to create a representative model of weather across cities. Similarly, in VacationPy we used the weather data collected in WeatherPy (from the cities.csv file) to plan future vacations and select hotels. We used hvpyplot and the Geoapify API documentation to visualize the data.
# Process
We generated random geographic coordinates (latitude and longitude) and used the citipy library to find the nearest city for each combination. This gave us a list of over 500 cities to analyze.
We used the OpenWeatherMap API to fetch weather data for each city. The data included parameters like temperature, humidity, cloudiness, and wind speed.
Once we have the weather data, we performed data analysis and visualization to understand weather patterns across different cities. We created scatter plots, regression analysis, and heatmaps to identify any correlations between weather parameters and latitude.
For VacationPy, we used Holoviews and Hvplot to create a map plot based on cities data with humidity values. We also narrowed down the data to fit into ideal weather conditions. And finally used Geoapify API to find hotels in radius distance of 10000m.
# conclusion 
we were able to bring out a comprehensive analysis of the weather across different cities and a better understanding of how weather changes with distance from the equator.The analysis in the notebook will provide insights into weather patterns worldwide and serve as a valuable resource for travelers, researchers, and anyone interested in understanding global weather trends.



# python-api-challenge

This repository consists of a challenge created using Pandas and Matplotlib via Jupyter. The challenge is divided into two parts: <br>

1. WeatherPy <br>

2.VacationPy <br>

APIs used here are: <br>
>OpenWeatherMap API <br>
>Geoapify API.<br>

Note: All the skills in this challenge were covered during our class work activities no extra resources or tutor sessions I used here.
--------------------------- <br>
OpenWeatherMap API Key

Geoapify API Key

<b> Follow the instructions in each website to get your API keys. Links for obtaining an API key: </b>

For the weather_api_key: https://openweathermap.org/
For the geoapify_key: https://www.geoapify.com/get-started-with-maps-api

---------------------------------

<b> Part 1: WeatherPy </b>
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities. 
<b> Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude </b>
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

<b> Requirement 2: Compute Linear Regression for Each Relationship </b>
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

<b>Part 2: VacationPy </b>
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started. Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.
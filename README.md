# Python-API-Challenge

## Background

Data has the power to answer questions in a definitive way.
This project uses Python requests, APIs, and JSON traversals to answer the question: "What is the weather like as we approach the equator?"
It may be obvious that the temperature increases as one approaches the equator, but this project aims to provide data-driven proof
This activity is broken down into two deliverables, WeatherPy and VacationPy

## Objectives

Used the NumPy module to generatethe weather of over 500 cities of varying distances from the equator.
Use the citipy module to list the nearest city to the latitudes and longitudes.
Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
Parse the JSON data from the API request.
Collect the following data from the JSON file and add it to a DataFrame:

City, country, and date

Latitude and longitude

Maximum temperature

Humidity

Cloudiness

Wind speed

Current weather description.

Filter the Pandas DataFrame based on temperature.

created a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed.

Narrow down the  DataFrame to find your ideal weather condition:

A max temperature lower than 27 degrees but higher than 21

Wind speed less than 4.5 m/s

Zero cloudiness

For each city, used the Geoapify API to find the first hotel located within 10,000 meters of your coordinates

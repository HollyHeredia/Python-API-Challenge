# Weather Analysis
This repository contains two projects to study the weather using API to openweathermap.org and also uses Matplotlib, Pandas, Numpy, and Gmaps.

The WeatherPy folder contains code to pull a table from the OpenWeatherMap API and use the information to make scatter plots comparing latitude to temperature, cloudiness, humdity, and wind speed. The images of these plots can be found in the output folder.

The VacationPy folder contains code to pull a table from Google Places and make a heat map through Google. It for hotels after narrowing down the list to only cities with "ideal" weather conditions and adds the hotels to map with pins that contain some basic information regarding the hotel. This notebook outputs the dataframe pulled from the API call from WeatherPy into a csv file.

### Python-API-Challenge###


This activity is broken down into two deliverables, WeatherPy and VacationPy.

**Part 1: WeatherPy**
In this deliverable, the goal is to create a Python script to visualize the weather of over 500 cities of varying distances from the equator. It was done using the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and problem-solving skills to create a representative model of weather across cities.

For this part, the WeatherPy.ipynb Jupyter notebook source was provided in the starter code ZIP file. 
To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

*Requirement 1:*

#Create Plots to Showcase the Relationship Between Weather Variables and Latitude
#Create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

*Requirement 2:*
Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. 
Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). Here the method used for it was by defining a function in order to create the linear regression plots.

create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image

The following plots are required:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

**Part 2: VacationPy**
In this deliverable, weather data skills were used to plan future vacations. Also, Jupyter notebooks, the geoViews Python library, and the Geoapify API were used.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help get started.

The main tasks was to use the Geoapify API and the geoViews Python library and employ Python skills to create map visualizations.

#Requirements#

1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
   
2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
A max temperature lower than 27 degrees but higher than 21
Wind speed less than 4.5 m/s
Zero cloudiness

4. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

5. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

6. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:

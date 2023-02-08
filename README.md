# python-api-challenge
This is an assignment that I completed for the George Washington University Data Analytics Bootcamp, focused on analysis and visualization in Python using Jupyter Notebook and displaying my understanding of using API's to create datasets and visuals.


## Organization
Within "python-api-challenge" you will find this "README.md" file which provides an explanation of my analysis. You will also 
find the files, "WeatherPy", and "VacationPy" which contains my Python code in a Jupyter Notebook file for two API analyses. There 
is also a folder marked "output_data" which contains a csv file of the cities that I analyzed as well as four visualizations of
the relationships between variables in these cities. Each graph is labeled to show which relationship it represents as well as the 
date that the information was received.

## Background

For this assignment we generated a list of over 500 cities at varying distances from the equator and then analyzed their Weather
patterns in addition to constructing a list of cities with ideal weather conditions (from my perspective) and adding a list of 
local hotels that could be stayed in while visiting each.

### WeatherPy has the following objectives

The first objective of this analysis was to create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

The second objective of this analysis was to construct separate plots of the Northern Hemisphere and Southern Hemisphere. Then
create a series of scatter plots including the linear regression line, the model's formula, and the r values which focus on the
following relationships:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

### VacationPy has the following objectives

First generate a dataframe of over 500 random cities, then produce a map that displays a point for every city.

Create a new dataframe with only cities that feature my ideal weather conditions, and add a hotel within 10,000 metres as a
column.

Then make sure the hotel name and the country are displayed as additional information in the hover message for each city in the
map.


## Insights
In WeatherPy:
It can be observed that the Northern Hemisphere has a strong relationshp between Maximum Temperature and Latitude with an r squared value of .70. This relationship persists in the southern hemisphere, but is not as strong, with an r squared value of only .24. This makes sense, as the closer one gets to either the Arctic or the Antarctic the colder it generally gets. But there seems to be much more variability in the Southern Hemisphere leading to a weaker relationship between these factors.

We can see that Humidity and Latitude have a weak relationship in the Nothern Hemisphere with an r squared value of .22 and a non-existent relationship in the Southern Hemisphere with an r squared value of .06

Here we can see the lack of a relationship between Cloudiness and Latitude with r squared values of .04 in the Northern Hemisphere and .07 in the Southern Hemisphere.

Finally, here we can see the lack of a relationship between Wind Speed and Latitude with r squared values of .03 in the Northern Hemisphere and .09 in the Southern Hemisphere.

In VacationPy, it can be observed that the majority of cities that met my weather preferences were located in Central America and the northern half of South America. All of the cities were closer to the equator than to either pole.


# python-api-challenge
For this challenge, api calls were done to get data for the weather in cities around the world and to find hotels withing cities that meet my definition of a nice weather vacation spot.  In the first part of the project, the WeatherPy file, I collected a list of city names from the citipy library and then ran those through a for loop in order to call its individual weather stats from openweathermap.org and store them in a csv file.  With that file, I ran scatter plot comparisons between:
-	Max Temperature vs Latitude
-	Humidity vs Latitude
-	Cloudiness vs Latitude
-	Wind Speed vs Latitude
After that, the same comparisons were made with the northern and southern hemispheres.  Line regression was used in an attempt to find any conclusions that could be drawn from the data.  The results for those individual analysis are in the ipynb file.  In the second file, VacationPy,  I took the cities csv file created in the first half of the project and created a new data frame that I cut down to cities that fit my ideal vacation weather.  Using that shortened data frame, I made individual calls to the geoapify.com website in order to get the closest hotel information for each city.  I then plotted that information on a map listing the city name, the hotel available, and the country which it is located in.

# Installation
This code should be run on a PythonData virtual kernel but will probably run on a Python 3 kernel just as well.  You must install citipy library into your system via github ,in order to gather the list of cities in the WeatherPy file and install hvplot in order to see the map outputs in the VacationPy file. Make sure that you have a folder labeled “output data” to receive the csv file of the city weather api calls as well as the PNG copies of the scatter plots.   

# Resources
For this project, information was gathered from the homework and external website.  All sources are commented in within the code if it was from a non-homework site.

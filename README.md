# World_Weather_Analysis
Module_6
**Purpose**

The purpose of this challenge is to use enhance the PlanMyTrip app using weather description data retreived during this module. Then using that information input potential prefrences into the code and find travel destinations and nearby hotels. From a generated list of cities from the temerature preferences we will select for cities and create a travel route using the Geoapify Routing API. 

**Results** 

Using the code and API and Geoapify API keys we randomly generated 2,000 pairs of latitudes and longitudes and found the nearest cities using citipy module. Then using pandas dataframes and geoviews we selected cities that met the weather conditions we set as parameters and displayed those on a map. We then found nearby hotels for those cities of choice, selected for random cities to create a driveable travel route and plotted that on a map. 

**Analysis**

One issue that I ran into was that my temperatures were very high and I could not account for that. I just had to be mindful when choosing the min and max temps to select a range that was shown in my data. Another issue I found was the original cities I chose were in Mexico, Panama, and Colomnbia, but because it was a driving route I kept getting errors since it is not actually possible to drive this route. Once new cities were chosen the error went away. 
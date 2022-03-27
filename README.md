# World_Weather_Analysis

This has been an application work of setting up a travel itinerary and lay a route from four cities.

The cities were generated from a randomly generated list of coordinates with the random.uniform method from Numpy and then selecting the closed cities to those coordinates with a call to the open wheather API.

Once we get the cities in a data frame, and assign the weather metrics from the API call, we take client's preference for temperature from an imput box and select the cities that meet the criteria in a map thanks to the google maps api.

Finally, the itinerary is created with a route around the four cities displaying markers with hotel information from the given cities.

Each deliverable contains the code and images for the data frames and maps that were created.

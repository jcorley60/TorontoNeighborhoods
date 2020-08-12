# TorontoNeighborhoods
This is an exploration of Toronto's neighborhoods and what venues they have to offer.  

Toronto, ON, Canada's neighborhoods are found and specified with latitude/longitude.
An API call is made to Foursquare to gather venue information based upon the geographical coordinates of respective neighborhoods.  
Pandas Dataframes are employed heavily in data analysis.  
Onehot encodings are made to separate venues by category. 
Finally SciKit-Learn's kMeans() function is utilized in order to classify neighborhoods according to most common venues.

Visualization of data occurs throughout using Folium maps.

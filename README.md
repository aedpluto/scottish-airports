# Scottish Airports
This project analyse all the direct commercial internal airport connections in Scotland. Data was collected by hand by looking through each airport's list of destinations on their website.

First the networks are mapped as a network with networtx in Python. Then this is plotted on a map with cartopy to put the locations in context.

The map used is a Plate Carrée projection, which preserves distances beetween different latitudes and longitudes, in order to make plotting simple and consistent.

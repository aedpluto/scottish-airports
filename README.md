# Scottish Airports
This project analyses all the direct commercial internal airport connections in Scotland. Data was collected by hand by looking through each airport's list of destinations on their website.

First the airports are mapped as a network with networtx in Python. Then they are plotted on a map with cartopy to put the locations in context. A written report analysing the importance of each airport for Scotland's air infrastructure can be found in the "Written report" folder.

The map used is a Plate Carrée projection, which preserves distances beetween different latitudes and longitudes, in order to make plotting simple and consistent.

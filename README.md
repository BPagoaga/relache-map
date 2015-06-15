# relache-map

This script allows to build a google map with google map api.

To locate the map :
- if a place is selected, then it will use the coordinates of the place, saved in a database
- if no place is selected, it will then use the default coordinates, which are the "Mairie de Bordeaux" coordinates.

For a reason I can't figure out, the map isn't displayed if no place is selected. The script is just not launched at all, probably because of the way the initialize() function works in the google api.

Pls note that I tested the script also while replacing the "var contentString = '\<h2>'+data+'\</h2>';" by "var contentString = '\<h2>Hello\</h2>';". 

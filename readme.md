# Using Python and Javascript to create an interactive map
For a field trip by the University of Vienna and the University of Ljubjliana to the Großglockner area in Austria, the participtating teams designed a map of the area from scratch. My teams chose a "Photo Guide Map" of the area. 

While my collegue Raphael Stiegl produced the map tiles (than can not be shown on GitHub du to data regulation), I chose to create an interactive layer incorperating [Flicker](https://flickr.com/) pictures as well as our own geotagged pictures during the field trip.

The repository shows the code but does not provide a completed version of the map with all the data.

The two python notebooks were used to preprocess the Flicker and our own data. The relevant Metadata (e.g. Geotags, dates, owners) are put into a string and are then hardcoded into the javascript code for the map to avoid any data loading.
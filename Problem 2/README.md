## Problem 2
* The user wants to visualize the following geojson layers ([1](https://github.com/mysidewalk/interview/blob/master/assets/kc-neighborhoods.json), [2](https://github.com/mysidewalk/interview/blob/master/assets/kc-tracts.json)) together on a map along with a chart of their commuter population attributes in an interactive manner.

* INSTRUCTIONS:

* Firstly download the 'web server for chrome' extension for the chrome browser.
* Place all the files i.e., index.html, index.css and visualize.js into a file and give the location of this file in the web server for chrome extension.
* Load the server and open the index.html to view the visualization.

* ASSUMPTION:

* This visualization is done in D3.js and the mapbox is used for the data to be generated on the maps.
* Both the geojson files are placed on the visualization to choose one of the json file to analyze.
* When neighborhood data is selected the data regarding the commute of the people in the kansas city are mapped. 
* The area where the maximum of people commute by a particular type of commute then area is filled with the corresponding color as shown on the legend at the bottom right corner.
* For example harlem area in the neighborhood data is mostly filled with orange because the people in that area are commuting mostly through carpool.

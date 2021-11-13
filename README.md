# Mapping_Earthquakes

## Project Goal
- The purpose of this project is to visually show the differences between the magnitudes of 
  earthquakes all over the world for the last seven days.
- It use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates 
  and the magnitudes of earthquakes for the last seven days. Then add the data to a map.
- In this project we use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the 
  earthquakes from the GeoJSON data. We then use the Leaflet library to plot the data on a Mapbox map through an 
  API request and create interactivity for the earthquake data.


## Results
The results of the analysis was deployed on a webpage using html and javascript. The interactive webpage can be found here: https://dshetty100.github.io/Plotly_Bellybutton_Biodiversity/

The display below shows the map of earthquakes of varying amgnitude around the world in the past 7 days along with tectonuc plate.
The color and the size of the circles indicate the magnitude and the depth of the earthquake, respectively. The orange lines indicate the tectonic plates.
The earthquake GeoJSON data was taken from, https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson and the tectonic plate GeoJSON data was taken from, 
https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json

![Figure1](/Images/Fig1.png)

The display below shows the map of major earthquakes with magnitude greater than 4.5 around thw world in the past 7 days.
The major earthquake GeoJSON data was taken from, https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

![Figure2](/Images/Fig2.png)

The display below shows a third map style (Dark) added to the above map.

![Figure3](/Images/Dark_map_fig3.png)

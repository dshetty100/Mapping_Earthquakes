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

### 1. Satellite map of earthquakes around the world in the past 7 days

The display below shows the map of earthquakes of varying magnitude around the world in the past 7 days along with the tectonic plate.
The color and the size of the circles indicate the magnitude and the depth of the earthquake, respectively. The legend in the bottom right side of the map corresponds to the earthquakes magnitude. The orange lines indicate the tectonic plates.
The earthquake GeoJSON data was taken from, https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson and the tectonic plate GeoJSON data was taken from, https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json

![Figure1](/Images/Fig1.png)

### 2. Satellite map of major earthquakeswith magnitude 4.5+ around the world in the past 7 days
The display below shows the map of major earthquakes with a magnitude greater than 4.5 around the world in the past 7 days.
The major earthquake GeoJSON data was taken from, https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

![Figure2](/Images/Fig2.png)

### 3. Dark map of earthquakes around the world in the past 7 days
The display below shows a third map style (Dark) added to the above map.

![Figure3](/Images/Dark_map_fig3.png)

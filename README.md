# Mapping_Earthquakes

## Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. To do this, a URL for GeoJSON earthquake data from the USGS website is utilized to retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days where the data is then added to a map. Plate tectonic boundary lines were also added for visual reference.

## Oilfield Application

As oil and gas operators continue their completions operations utilizing hydraulic fracturing, questions on whether or not earthquakes come from these activities continue to be asked. This data can be combined with oilfield operations data to validate whether or not hydraulic fracturing operations were occuring in the vicinity of the earthquakes when they occured.

## Project Output Screenshot
<img height="100%" width="100%" src="https://github.com/smyoung88/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/earthquake_map2.png">

## Resources
JavaScript and the D3.js library is utilized to retrieve coordinates and magnitudes of earthquakes from the GeoJSON data. The Leaflet library is used to plot the data on a Mapbox map through an API request where it is then enhanced to create interactivity for the earthquake data.

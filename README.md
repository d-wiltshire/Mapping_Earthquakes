# Mapping_Earthquakes

The goal of this exercise was to use JavaScript, d3.json, and Leaflet to plot earthquake data on a geographical map. The information plotted includes the earthquake's location and magnitude, and tectonic plate lines were also added to the map. 

## Deliverable 1: Add Tectonic Plate Data
The first deliverable involved plotting tectonic line data on the map. Using d3.json() and adding the data using the geoJSON() layer, the tectonic plate LineString data was added to the overlay object with the original earthquake data.

## Deliverable 2: Add Major Earthquake Data
In the second deliverable, a second overlay object was added for major earthquake data. This overlay object was in addition to the original earthquake data, and the "major earthquakes" overlay layer included only earthquakes with a magnitude over 4.5. New colors were used to distinguish these major earthquakes from the others (between 4.5 and 5.0, maroon; between 5.0 and 6.0, purple; and over 6.0, black). The magnitude was also reflected in the size of the circle marker, and a popup marker was added that displays the magnitude and location of the earthquake.

## Deliverable 3: Add an Additional Map
The third deliverable involved adding a third base layer, "Dark," to the map (in addition to "Streets" and "Satellite").

The resulting map showing all three deliverables can be seen below:

![earthquakes2](https://user-images.githubusercontent.com/100863488/170739615-3f3ef1d8-6f71-4996-85ef-38689edb9c44.png)

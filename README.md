🚆 Train Network Mapping – GeoJSON + Leaflet

An interactive map visualization of a simplified train network in North Rhine–Westphalia (Germany), built using Leaflet.js, GeoJSON, and custom dataset modeling.
This project demonstrates how to encode spatial data (stations + railway lines) using GeoJSON and how to render them on a web map.

📌 Features
🗺️ Interactive Leaflet Map
 - Displays train stations as custom red circular icons.
 - Renders multiple rail lines using different colors.
 - Pop-up windows show detailed information for each station and train line.
 - Map auto-fits to the extent of all features.

🚉 Train Stations (Points)

Defined as GeoJSON Feature objects with:

 - Station ID
 - Name
 - City

Train lines that stop there

Coordinates (Point geometry)

🚆 Train Lines (LineString)


The map will be live at:
https://german-trainlines.netlify.app/


🧩 Technologies Used
 - Leaflet.js (interactive map)
 - OpenStreetMap tiles
 - GeoJSON (data modeling)
 - JavaScript (map logic)
 - HTML + CSS



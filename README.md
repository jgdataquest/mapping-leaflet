# GeoJSON

In this activity, we will plot markers on a map to represent the occurrence of earthquakes. We will be working with GeoJSON from the [USGS](http://earthquake.usgs.gov) to achieve this.

## Instructions

1. Open the [logic.js](Unsolved/logic.js) file.

2. Your starter code places an API call to the USGS Earthquake Hazards Program API. Take a moment to study the "features" array that is extracted from the response.

3. Add some logic to create a GeoJSON layer containing all features retrieved from the API call and add it directly to the map. You can reference today's previous activities as well as [Leaflet's Docs for GeoJSON](http://leafletjs.com/examples/geojson/).

4. Create an `overlayMaps` object using the newly created earthquake GeoJSON layer. Pass the `overlayMaps` into the layer control.


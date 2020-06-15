# Bike Routes

A free and open source database of bike routes.

The routes can be easily explored with our application: https://bikeroutes.github.io/Explorer/

## Can I contribute?

Please do :)

This project is open source: you can propose any change or addition by opening a pull request.

This repository contains all the route data, so you should open a pull request here if you want to add or modify a route.

To contribute to the "Explorer" app, refer instead to https://github.com/BikeRoutes/Explorer

## How to export data from Strava

### Strava Activity

1. Open an activity on the Strava website
2. Click on "..." in the left sidebar
3. Click "Export GPX"
4. Convert it to geoJSON

### Strava Route

It's often worth converting a Strava Activity to a Strava Route before exporting it, because in this way you can leverage the powerful Strava Route editor to refine your route details.

_Unfortunately the Route Editor is now only available to Strava paying subscribers. [Bikemap](https://www.bikemap.net/) offers a similar route editor for free._

1. Open an activity on the Strava website
2. Click on "..." in the left sidebar
3. Click "Create Route"
4. Edit your route using the Route Editor
5. Click "Export GPX"
6. Convert it to geoJSON

## Useful tools

* You can easily convert a GPX file to geoJSON with [toGeoJSON](https://mapbox.github.io/togeojson/)

* If you plan a route using Google Maps, you can use [GPS Visualizer](https://www.gpsvisualizer.com/convert_input) to convert it to GPX

* [Bikemap](https://www.bikemap.net/) has a powerful visual route editor that can import and export GPX files

* [geojson.io](https://geojson.io) is a simple geoJSON web viewer with limited editing functionalities

* [uMap](https://umap.openstreetmap.fr/en/) is a more advanced map editor that supports geoJSON

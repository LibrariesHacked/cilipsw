GIS data
========


## Geocoding and reverse-geocoding

Geocoding and reverse geocoding are ways of matching address and location data with geo-coordinates.

- **Geocoding:** Address -> Geo-coordinates.  Usage example: Plotting a user address search onto a map.
- **Reverse geocoding:** Geo-coordinates -> Address.  Usage example: taking coordinates retrieved from GPS to determine current location.
- **Geofencing:**  A feature in a software program that uses the global positioning system (GPS) or radio frequency identification (RFID) to define geographical boundaries. A geofence is a virtual barrier.

## Points, lines, and polygons

Typically when dealing with geo-spatial data, this will be in the form of Points, Lines, and Polygons.

- **Points** - Individual locations made up of a single coordinate set.
- **Lines** - Linear features made up of coordinates such as route lines.
- **Polygons** - Bounded areas (shapes) made up of coordinates such as local authority boundaries and geofences.

## File formats

There are many different formats for storing geo data.  These are a few of them.

| Format | Description | Example |
| ------ | ----------- | ------- |
| GeoJSON | JavaScript Object Notation (JSON) style geo data. | [/data/Somerset School Catchment Areas 2014-15.geojson](Somerset School Catchment Areas) |
| Shapefiles | Format developed by ESRI for storing geospatial data.  More than one file!  | [/data/]() | 
| KML | XML type format for storing geospatial data. Used by Google Earth and Google fusion tables. | [SomersetLibraries](/data/SomersetLibraries.kml) |

## GIS software

The traditional way of working with GIS data is through Desktop applications

- [ESRI ArcDesktop](http://www.esri.com/software/arcgis/arcgis-for-desktop) - World leader for GIS software
- [MapInfo](http://www.pitneybowes.com/us/location-intelligence/geographic-information-systems/mapinfo-pro.html) - Acquired by Pitney Bowes Business Insight
- [Quantum GIS](http://qgis.org/en/site/) - Open Source option.  Brilliant.

Download and install: [Quantum GIS](http://qgis.org/en/site/)

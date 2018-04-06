Routes and travel
=================

GIS data allows for quick analysis of distance. 

- The library postcode lottery for example groups areas of the country by distance to a library
- The England Library visualisation creates catchment areas based upon assiging each area to their nearest library

This is often seen in analysis of locations of libraries, particularly during times of consultations.

An 'easy' option is to simply plot a radius around each library and ensure the whole authority is with X distance to a library.

There are problems with this though:

- What if there is a big river between you and a library? It may be the nearest, but it may also be a long round trip to get there.
- What about different travel types and accessibility? 3 miles on a motorway is very different to 3 miles across a city. Some routes may not be pedestrian.

![Image of river at Topsham](https://raw.githubusercontent.com/LibrariesHacked/geography-librarydata/master/images/river.png)

**Travel time and real travel distance** is often more important than just straight line distances.

Open Street Map
---------------

[Open Street Map](https://www.openstreetmap.org/) is a huge online database of GIS data to create a map of the world. It includes all you would expect on a map such as roads, paths, places, and green spaces.

Having open road data means we can do more complex route analysis.

- Road speeds give an indication of how fast cars can travel on a road.
- Road inclination will give further data. Cars may not care too much about steep hill, cyclists certainly will!
- Historic traffic data can be used to give further indications of travel times.

Open Street Map data is used in [Open Route Service](https://openrouteservice.org/), open source and developed by the University of Heidelberg. Free APIs are also included to calculate routes and route times for different travel types.
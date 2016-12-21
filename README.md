# leaflet-socrata
Leaflet maps with external Socrata open data feed

## Demos

Working examples where Socrata data includes separate columns for latitude, longitude

example 1
- data https://data.cityofnewyork.us/Social-Services/Halloween-Noise-Lat-Long/25yv-wyir
- map https://jackdougherty.github.io/leaflet-socrata/index.html
- credit http://stackoverflow.com/questions/33684726/socrata-soda-api-call-via-jquery-not-returning-the-entire-dataset

example 2
- data https://opendata.demo.socrata.com/Government/Kentucky-Farmers-Market-Map/3bfj-rqn7
- map https://jackdougherty.github.io/leaflet-socrata/index2.html
- credit https://github.com/chriswhong/simpleSodaLeaflet

## Problem

How to rewrite the code when latitude and longitude are combined in one point data field (geom) inside Socrata?

example 3
- data from Hartford Open Data (with "geom" column) https://data.hartford.gov/Public-Health/Current-Class-1-Class-4-Food-Establishments/xkvv-76v8
- map (not yet working) https://jackdougherty.github.io/leaflet-socrata/index3.html
- console error: Invalid LatLng object: (undefined, undefined)


## to do later

See how Chris Whong uses soda-leaflet to limit results to most recent 7 days
- data https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9
- code repo https://github.com/chriswhong/soda-leaflet/

fix control layers for legend

https://jackdougherty.github.io/leaflet-socrata/index-control-layers.html

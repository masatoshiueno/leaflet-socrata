# leaflet-socrata
testing leaflet maps with external Socrata open data feed

## demo maps

https://jackdougherty.github.io/leaflet-socrata/index.html

this demo currently works when Socrata data source designates fields as latitude, longitude

data source: https://data.cityofnewyork.us/Social-Services/Halloween-Noise-Lat-Long/25yv-wyir

## to do

1) How to make control layers work properly in similar example?

https://jackdougherty.github.io/leaflet-socrata/index-control-layers.html

2) How to make this work when lat and long are buried inside a geom field in the Socrata source data?

Hartford source data: https://dev.socrata.com/foundry/data.hartford.gov/egxr-myum

Idea: See how CWong did this with this data:
https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9

and this section of code from his soda-leaflet
https://github.com/chriswhong/soda-leaflet/blob/master/js/script.js

![OSM logo](https://wiki.openstreetmap.org/w/images/7/79/Public-images-osm_logo.svg)
# Localized Nominatim Search with OpenLayers 2.x
Easy to use example how to search with Nominatim, return the results and result categories in a specific language and how to display it on a simple map with OpenLayers.
## Example
An example with english localisation is currently running [here](http://www.codegeo.de/search_example/). Search for Moscow to see how it returns english names instead of "Москва́".
## Installation
- All code except OpenLayers 2 is included 
- Download and unpack OpenLayers 2.x 
- Change path to OpenLayers.js in line 19 in index.hml 
- Change language code you want in line 38 in index.hml 
- Ensure all translations for the selected language code are included in nominatim-i8n.csv 
- Change name and location of the lockfile in line 27 of mapquestjs.php 

Due to the limits of the public Nomination server, it use a lockfile to limit requests to max 1 request per second.

## Team
Most of the work was done by [Max](https://wiki.openstreetmap.org/wiki/User:Maxbe).

## Support
No support. But you can try to contact me at thomas@codegeo.de


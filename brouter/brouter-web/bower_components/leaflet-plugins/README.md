Leaflet plugins
============

What ?
------

Miscellaneous Leaflet plugins for services that need to display
route information and need satellite imagery from different providers.
Currently it consists of:

 - Vector layers (`layer/vector/`):
   * GPX
   * KML
   * TOPOJSON

 - Providers (`layer/tile`):
   * Google - using Google Maps API v3;
   * Yandex - using Yandex Maps API v2;
   * Bing - with proper attribution.

All these providers are implemented with respect to terms of use.

Also there are some useful control plugins (`control/`):

 * Permalink - OpenLayers compatible permanent link with support for storing
   location data in hash part (#lat=...);
 * Distance - simple tool to measure distances on maps


Compatibility
------
 - Tested with: Leaflet 0.7.x
 - For use with Leaflet 1.0.x see branch `leaflet_one`


Where ?
------

Homepage : https://github.com/shramov/leaflet-plugins

Downloads : https://github.com/shramov/leaflet-plugins/releases

npm : https://www.npmjs.org/package/leaflet-plugins

cdnjs : https://cdnjs.com/libraries/leaflet-plugins

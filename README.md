# Esri Leaflet Vector Basemap Proof-of-Concept

This is a proof of concept for using the [ArcGIS Online Vector Basemaps](http://www.arcgis.com/home/group.html?id=30de8da907d240a0bccd5ad3ff25ef4a&focus=layers) with [Esri Leaflet]()https://github.com/Esri/esri-leaflet. It uses https://github.com/mapbox/mapbox-gl-leaflet and a custom fork of [mapbox-gl-js](https://github.com/patrickarlt/mapbox-gl-js/tree/esri-leaflet-renderer) which is based off of https://github.com/Esri/mapbox-gl-js/tree/indexed-vector-sources and https://github.com/Esri/vector-tile-js/tree/clipping-logic.

### Caveats

* Mostly untested. Works against the basemap styles listed https://developers.arcgis.com/javascript/beta/api-reference/esri-layers-VectorTileLayer.html#url
* Slight flickering around the edges when "flick-panning"
* Leaflet 0.7.7 only
* No proper handling of attribution

### Licensing
Copyright 2015 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

> http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [LICENSE](./LICENSE) file.

[](Esri Tags: ArcGIS Web Mapping Leaflet)
[](Esri Language: JavaScript)
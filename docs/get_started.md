# Get Started

## Godream (Geo-dream)
Godream (Geo-dream) is a library that contain geospatial tools for RS&GIS analyze or geospatial analyze in python language. This appears to be a Python library specifically developed to assist in the analysis of geospatial data, with a focus on remote sensing and GIS applications. Such a library would likely provide functions and tools to manipulate, process, and visualize geospatial data, making it easier for users to perform complex analyses in these domains [pypi.org](https://pypi.org/project/Godream/).

[(How to create new environment)](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands)

Require Python version 3.9 ⚠️

Require to install GDAL (choose for Python 3.9) ⚠️

[How to install with Wheel file(.whl)](https://www.educative.io/answers/how-to-install-a-python-package-with-a-whl-file)

[Download GDAL from Wheel](https://github.com/DreamPTK/rice-detection/tree/main/dream_river/gdal_lib)


## Activate your environment 

    conda activate 'your environment'


## Installation

    pip install Godream


## Launch Jupyter notebook

    jupyter notebook


## Import libraries

```python
import Godream
```

## Try to run first command

## Import library

```python
from Godream.plotimg import show_map 
```

## Create an intercative map

```python
show_map()
```

<div style="width:100%;"><div style="position:relative;width:100%;height:0;padding-bottom:60%;"><span style="color:#565656">Make this Notebook Trusted to load map: File -> Trust Notebook</span><iframe srcdoc="&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;

    &lt;meta http-equiv=&quot;content-type&quot; content=&quot;text/html; charset=UTF-8&quot; /&gt;

        &lt;script&gt;
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        &lt;/script&gt;

    &lt;style&gt;html, body {width: 100%;height: 100%;margin: 0;padding: 0;}&lt;/style&gt;
    &lt;style&gt;#map {position:absolute;top:0;bottom:0;right:0;left:0;}&lt;/style&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://code.jquery.com/jquery-1.12.4.min.js&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js&quot;&gt;&lt;/script&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css&quot;/&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css&quot;/&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css&quot;/&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css&quot;/&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css&quot;/&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css&quot;/&gt;

            &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no&quot; /&gt;
            &lt;style&gt;
                #map_756e14362e49d94908abe18ad6a8e08d {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            &lt;/style&gt;

    &lt;script src=&quot;https://unpkg.com/leaflet-control-geocoder/dist/Control.Geocoder.js&quot;&gt;&lt;/script&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://unpkg.com/leaflet-control-geocoder/dist/Control.Geocoder.css&quot;/&gt;
    &lt;script src=&quot;https://cdnjs.cloudflare.com/ajax/libs/leaflet.fullscreen/1.4.2/Control.FullScreen.min.js&quot;&gt;&lt;/script&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdnjs.cloudflare.com/ajax/libs/leaflet.fullscreen/1.4.2/Control.FullScreen.min.css&quot;/&gt;
    &lt;script src=&quot;https://cdnjs.cloudflare.com/ajax/libs/leaflet-locatecontrol/0.66.2/L.Control.Locate.min.js&quot;&gt;&lt;/script&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdnjs.cloudflare.com/ajax/libs/leaflet-locatecontrol/0.66.2/L.Control.Locate.min.css&quot;/&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/gh/ljagis/leaflet-measure@2.1.7/dist/leaflet-measure.min.js&quot;&gt;&lt;/script&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/gh/ljagis/leaflet-measure@2.1.7/dist/leaflet-measure.min.css&quot;/&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/gh/ardhi/Leaflet.MousePosition/src/L.Control.MousePosition.min.js&quot;&gt;&lt;/script&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/gh/ardhi/Leaflet.MousePosition/src/L.Control.MousePosition.min.css&quot;/&gt;
    &lt;script src=&quot;https://cdnjs.cloudflare.com/ajax/libs/leaflet.draw/1.0.2/leaflet.draw.js&quot;&gt;&lt;/script&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdnjs.cloudflare.com/ajax/libs/leaflet.draw/1.0.2/leaflet.draw.css&quot;/&gt;

            &lt;style&gt;
                #export {
                    position: absolute;
                    top: 5px;
                    right: 10px;
                    z-index: 999;
                    background: white;
                    color: black;
                    padding: 6px;
                    border-radius: 4px;
                    font-family: &#x27;Helvetica Neue&#x27;;
                    cursor: pointer;
                    font-size: 12px;
                    text-decoration: none;
                    top: 90px;
                }
            &lt;/style&gt;

&lt;/head&gt;
&lt;body&gt;


            &lt;div class=&quot;folium-map&quot; id=&quot;map_756e14362e49d94908abe18ad6a8e08d&quot; &gt;&lt;/div&gt;

    &lt;a href=&#x27;#&#x27; id=&#x27;export&#x27;&gt;Export&lt;/a&gt;
&lt;/body&gt;
&lt;script&gt;


            var map_756e14362e49d94908abe18ad6a8e08d = L.map(
                &quot;map_756e14362e49d94908abe18ad6a8e08d&quot;,
                {
                    center: [13.726, 100.514],
                    crs: L.CRS.EPSG3857,
                    zoom: 6,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );





            L.Control.geocoder(
                {&quot;collapsed&quot;: true, &quot;defaultMarkGeocode&quot;: true, &quot;position&quot;: &quot;topleft&quot;, &quot;show&quot;: true}
            ).on(&#x27;markgeocode&#x27;, function(e) {
                map_756e14362e49d94908abe18ad6a8e08d.setView(e.geocode.center, 11);
            }).addTo(map_756e14362e49d94908abe18ad6a8e08d);



            L.control.fullscreen(
                {&quot;forceSeparateButton&quot;: false, &quot;position&quot;: &quot;topleft&quot;, &quot;title&quot;: &quot;Full Screen&quot;, &quot;titleCancel&quot;: &quot;Exit Full Screen&quot;}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);


            var locate_control_86be0c50fd5f4f03d714c8e4467c29e5 = L.control.locate(
                {}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);



            var measure_control_d67846a47b5432ca2b0dd5cffd2fa55b = new L.Control.Measure(
                {&quot;position&quot;: &quot;bottomright&quot;, &quot;primaryAreaUnit&quot;: &quot;sqmeters&quot;, &quot;primaryLengthUnit&quot;: &quot;meters&quot;, &quot;secondaryAreaUnit&quot;: &quot;acres&quot;, &quot;secondaryLengthUnit&quot;: &quot;miles&quot;});
            map_756e14362e49d94908abe18ad6a8e08d.addControl(measure_control_d67846a47b5432ca2b0dd5cffd2fa55b);



            var mouse_position_f54cb8c41005c57b2313e6f3e5f5ec17 = new L.Control.MousePosition(
                {&quot;emptyString&quot;: &quot;Unavailable&quot;, &quot;lngFirst&quot;: false, &quot;numDigits&quot;: 4, &quot;position&quot;: &quot;bottomleft&quot;, &quot;prefix&quot;: &quot;\u0026copy; GODream | Lat/Lon:&quot;, &quot;separator&quot;: &quot; | &quot;}
            );
            mouse_position_f54cb8c41005c57b2313e6f3e5f5ec17.options[&quot;latFormatter&quot;] =
                undefined;
            mouse_position_f54cb8c41005c57b2313e6f3e5f5ec17.options[&quot;lngFormatter&quot;] =
                undefined;
            map_756e14362e49d94908abe18ad6a8e08d.addControl(mouse_position_f54cb8c41005c57b2313e6f3e5f5ec17);


            var tile_layer_754ca668b713c627ba9a3b3d4cafd454 = L.tileLayer(
                &quot;https://mt1.google.com/vt/lyrs=p\u0026x={x}\u0026y={y}\u0026z={z}&quot;,
                {&quot;attribution&quot;: &quot;Google&quot;, &quot;detectRetina&quot;: false, &quot;maxNativeZoom&quot;: 18, &quot;maxZoom&quot;: 18, &quot;minZoom&quot;: 0, &quot;noWrap&quot;: false, &quot;opacity&quot;: 1, &quot;subdomains&quot;: &quot;abc&quot;, &quot;tms&quot;: false}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);


            var tile_layer_0d4a9f55b6f4f1c37b174c296961bc4e = L.tileLayer(
                &quot;https://mt1.google.com/vt/lyrs=s\u0026x={x}\u0026y={y}\u0026z={z}&quot;,
                {&quot;attribution&quot;: &quot;Google&quot;, &quot;detectRetina&quot;: false, &quot;maxNativeZoom&quot;: 18, &quot;maxZoom&quot;: 18, &quot;minZoom&quot;: 0, &quot;noWrap&quot;: false, &quot;opacity&quot;: 1, &quot;subdomains&quot;: &quot;abc&quot;, &quot;tms&quot;: false}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);


            var tile_layer_dbfe361b4c72b645eebd541452a32a61 = L.tileLayer(
                &quot;https://mt1.google.com/vt/lyrs=y\u0026x={x}\u0026y={y}\u0026z={z}&quot;,
                {&quot;attribution&quot;: &quot;Google&quot;, &quot;detectRetina&quot;: false, &quot;maxNativeZoom&quot;: 18, &quot;maxZoom&quot;: 18, &quot;minZoom&quot;: 0, &quot;noWrap&quot;: false, &quot;opacity&quot;: 1, &quot;subdomains&quot;: &quot;abc&quot;, &quot;tms&quot;: false}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);


            var tile_layer_e039c5397ce64cdf84f97b216cdd2ee8 = L.tileLayer(
                &quot;https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png&quot;,
                {&quot;attribution&quot;: &quot;OpenStreetMap&quot;, &quot;detectRetina&quot;: false, &quot;maxNativeZoom&quot;: 18, &quot;maxZoom&quot;: 18, &quot;minZoom&quot;: 0, &quot;noWrap&quot;: false, &quot;opacity&quot;: 1, &quot;subdomains&quot;: &quot;abc&quot;, &quot;tms&quot;: false}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);


            var tile_layer_995d0ca2152af443271dfedb8c542184 = L.tileLayer(
                &quot;https://basemap.sphere.gistda.or.th/tiles/sphere_hybrid/EPSG3857/{z}/{x}/{y}.jpeg?key=42B90819583344A789DA424BE70CDB61&quot;,
                {&quot;attribution&quot;: &quot;sphere.gistda&quot;, &quot;detectRetina&quot;: false, &quot;maxNativeZoom&quot;: 18, &quot;maxZoom&quot;: 18, &quot;minZoom&quot;: 0, &quot;noWrap&quot;: false, &quot;opacity&quot;: 1, &quot;subdomains&quot;: &quot;abc&quot;, &quot;tms&quot;: false}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);


            var tile_layer_c1d342ffae532c896f29bf439e0c3c19 = L.tileLayer(
                &quot;https://basemap.sphere.gistda.or.th/tiles/thailand_images/EPSG3857/{z}/{x}/{y}.jpeg?key=test2022&quot;,
                {&quot;attribution&quot;: &quot;sphere.gistda&quot;, &quot;detectRetina&quot;: false, &quot;maxNativeZoom&quot;: 18, &quot;maxZoom&quot;: 18, &quot;minZoom&quot;: 0, &quot;noWrap&quot;: false, &quot;opacity&quot;: 1, &quot;subdomains&quot;: &quot;abc&quot;, &quot;tms&quot;: false}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);


            var layer_control_4e89791911314ba13e390cb068a23a73 = {
                base_layers : {
                    &quot;Terrain&quot; : tile_layer_754ca668b713c627ba9a3b3d4cafd454,
                    &quot;Google Satellite&quot; : tile_layer_0d4a9f55b6f4f1c37b174c296961bc4e,
                    &quot;Hybrid&quot; : tile_layer_dbfe361b4c72b645eebd541452a32a61,
                    &quot;OpenStreetMap&quot; : tile_layer_e039c5397ce64cdf84f97b216cdd2ee8,
                    &quot;Gistda Hybrid&quot; : tile_layer_995d0ca2152af443271dfedb8c542184,
                    &quot;Gistda Satellite&quot; : tile_layer_c1d342ffae532c896f29bf439e0c3c19,
                },
                overlays :  {
                },
            };
            L.control.layers(
                layer_control_4e89791911314ba13e390cb068a23a73.base_layers,
                layer_control_4e89791911314ba13e390cb068a23a73.overlays,
                {&quot;autoZIndex&quot;: true, &quot;collapsed&quot;: true, &quot;position&quot;: &quot;topright&quot;}
            ).addTo(map_756e14362e49d94908abe18ad6a8e08d);
            tile_layer_0d4a9f55b6f4f1c37b174c296961bc4e.remove();
            tile_layer_dbfe361b4c72b645eebd541452a32a61.remove();
            tile_layer_e039c5397ce64cdf84f97b216cdd2ee8.remove();
            tile_layer_995d0ca2152af443271dfedb8c542184.remove();
            tile_layer_c1d342ffae532c896f29bf439e0c3c19.remove();


           var options = {
              position: &quot;topleft&quot;,
              draw: {&quot;circle&quot;: {&quot;allowIntersection&quot;: true}, &quot;marker&quot;: {&quot;allowIntersection&quot;: true}, &quot;polygon&quot;: {&quot;allowIntersection&quot;: true}, &quot;polyline&quot;: {&quot;allowIntersection&quot;: true}, &quot;rectangle&quot;: {&quot;allowIntersection&quot;: true}},
              edit: {&quot;featureGroup&quot;: null},
              }
            // FeatureGroup is to store editable layers.
            var drawnItems = new L.featureGroup().addTo(
                map_756e14362e49d94908abe18ad6a8e08d
            );
            options.edit.featureGroup = drawnItems;
            var draw_control_24c44b4aa7216ae43d230ebe5691612a = new L.Control.Draw(
                options
            ).addTo( map_756e14362e49d94908abe18ad6a8e08d );
            map_756e14362e49d94908abe18ad6a8e08d.on(L.Draw.Event.CREATED, function(e) {
                var layer = e.layer,
                    type = e.layerType;
                var coords = JSON.stringify(layer.toGeoJSON());
                layer.on(&#x27;click&#x27;, function() {
                    alert(coords);
                    console.log(coords);
                });
                drawnItems.addLayer(layer);
             });
            map_756e14362e49d94908abe18ad6a8e08d.on(&#x27;draw:created&#x27;, function(e) {
                drawnItems.addLayer(e.layer);
            });

            document.getElementById(&#x27;export&#x27;).onclick = function(e) {
                var data = drawnItems.toGeoJSON();
                var convertedData = &#x27;text/json;charset=utf-8,&#x27;
                    + encodeURIComponent(JSON.stringify(data));
                document.getElementById(&#x27;export&#x27;).setAttribute(
                    &#x27;href&#x27;, &#x27;data:&#x27; + convertedData
                );
                document.getElementById(&#x27;export&#x27;).setAttribute(
                    &#x27;download&#x27;, &quot;drawn_polygons.geojson&quot;
                );
            }


&lt;/script&gt;
&lt;/html&gt;" style="position:absolute;width:100%;height:100%;left:0;top:0;border:none !important;" allowfullscreen webkitallowfullscreen mozallowfullscreen></iframe></div></div>


<!-- ## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files. -->

[customer_map.html](https://github.com/user-attachments/files/23214552/customer_map.html)
<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_caa25e94b15caed6f2e9ef0fda8bfd95 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>

            <style>html, body {
                width: 100%;
                height: 100%;
                margin: 0;
                padding: 0;
            }
            </style>

            <style>#map {
                position:absolute;
                top:0;
                bottom:0;
                right:0;
                left:0;
                }
            </style>

            <script>
                L_NO_TOUCH = false;
                L_DISABLE_3D = false;
            </script>

        
</head>
<body>
    
    
            <div class="folium-map" id="map_caa25e94b15caed6f2e9ef0fda8bfd95" ></div>
        
</body>
<script>
    
    
            var map_caa25e94b15caed6f2e9ef0fda8bfd95 = L.map(
                "map_caa25e94b15caed6f2e9ef0fda8bfd95",
                {
                    center: [36.600875, -93.812325],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 4,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_e56b41a61e78b95745ea5b38260a75a7 = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {
  "minZoom": 0,
  "maxZoom": 19,
  "maxNativeZoom": 19,
  "noWrap": false,
  "attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors",
  "subdomains": "abc",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_e56b41a61e78b95745ea5b38260a75a7.addTo(map_caa25e94b15caed6f2e9ef0fda8bfd95);
        
    
            var marker_f77a399adb199950a6e6d1c46bb76a9e = L.marker(
                [40.7128, -74.006],
                {
}
            ).addTo(map_caa25e94b15caed6f2e9ef0fda8bfd95);
        
    
            var icon_fa0c582e1072f29272e6193617a177a7 = L.AwesomeMarkers.icon(
                {
  "markerColor": "blue",
  "iconColor": "white",
  "icon": "briefcase",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
        
    
        var popup_5dea3140926bd3f5c927b2aaf58b96f3 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f780f52ac428017e0e423a1e9569053d = $(`<div id="html_f780f52ac428017e0e423a1e9569053d" style="width: 100.0%; height: 100.0%;">     <b>Customer ID:</b> 1<br>     <b>Company:</b> Alpha Corp     </div>`)[0];
                popup_5dea3140926bd3f5c927b2aaf58b96f3.setContent(html_f780f52ac428017e0e423a1e9569053d);
            
        

        marker_f77a399adb199950a6e6d1c46bb76a9e.bindPopup(popup_5dea3140926bd3f5c927b2aaf58b96f3)
        ;

        
    
    
            marker_f77a399adb199950a6e6d1c46bb76a9e.bindTooltip(
                `<div>
                     Alpha Corp
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
                marker_f77a399adb199950a6e6d1c46bb76a9e.setIcon(icon_fa0c582e1072f29272e6193617a177a7);
            
    
            var marker_ddfa9c0aa3a35ce79cd4329cddd6c429 = L.marker(
                [34.0522, -118.2437],
                {
}
            ).addTo(map_caa25e94b15caed6f2e9ef0fda8bfd95);
        
    
            var icon_ab9c52991fbb2e218464ad2fd3c80020 = L.AwesomeMarkers.icon(
                {
  "markerColor": "blue",
  "iconColor": "white",
  "icon": "briefcase",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
        
    
        var popup_9301b552f00790505d4ca05f7e66df4d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_fbcfac95f4fbbf9fd91d8553cfc44095 = $(`<div id="html_fbcfac95f4fbbf9fd91d8553cfc44095" style="width: 100.0%; height: 100.0%;">     <b>Customer ID:</b> 2<br>     <b>Company:</b> Beta Ltd     </div>`)[0];
                popup_9301b552f00790505d4ca05f7e66df4d.setContent(html_fbcfac95f4fbbf9fd91d8553cfc44095);
            
        

        marker_ddfa9c0aa3a35ce79cd4329cddd6c429.bindPopup(popup_9301b552f00790505d4ca05f7e66df4d)
        ;

        
    
    
            marker_ddfa9c0aa3a35ce79cd4329cddd6c429.bindTooltip(
                `<div>
                     Beta Ltd
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
                marker_ddfa9c0aa3a35ce79cd4329cddd6c429.setIcon(icon_ab9c52991fbb2e218464ad2fd3c80020);
            
    
            var marker_06a2d922142efe66128687de379adf34 = L.marker(
                [41.8781, -87.6298],
                {
}
            ).addTo(map_caa25e94b15caed6f2e9ef0fda8bfd95);
        
    
            var icon_f30a063fb26a26591372b01f5c3500fd = L.AwesomeMarkers.icon(
                {
  "markerColor": "blue",
  "iconColor": "white",
  "icon": "briefcase",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
        
    
        var popup_26d12a198b8e3db22da1d17baf43d27c = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_bb5ad562fc19783e9c866f51386933ce = $(`<div id="html_bb5ad562fc19783e9c866f51386933ce" style="width: 100.0%; height: 100.0%;">     <b>Customer ID:</b> 3<br>     <b>Company:</b> Gamma Inc     </div>`)[0];
                popup_26d12a198b8e3db22da1d17baf43d27c.setContent(html_bb5ad562fc19783e9c866f51386933ce);
            
        

        marker_06a2d922142efe66128687de379adf34.bindPopup(popup_26d12a198b8e3db22da1d17baf43d27c)
        ;

        
    
    
            marker_06a2d922142efe66128687de379adf34.bindTooltip(
                `<div>
                     Gamma Inc
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
                marker_06a2d922142efe66128687de379adf34.setIcon(icon_f30a063fb26a26591372b01f5c3500fd);
            
    
            var marker_c91a8b42bd494d09fe52e3fb1bc5348f = L.marker(
                [29.7604, -95.3698],
                {
}
            ).addTo(map_caa25e94b15caed6f2e9ef0fda8bfd95);
        
    
            var icon_3885a2507498a4f582b926c27618952d = L.AwesomeMarkers.icon(
                {
  "markerColor": "blue",
  "iconColor": "white",
  "icon": "briefcase",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
        
    
        var popup_1dc94d46c830e4d915c274dbeaae17e7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_5d26f04f76069d720ed9ece5f0744501 = $(`<div id="html_5d26f04f76069d720ed9ece5f0744501" style="width: 100.0%; height: 100.0%;">     <b>Customer ID:</b> 4<br>     <b>Company:</b> Delta LLC     </div>`)[0];
                popup_1dc94d46c830e4d915c274dbeaae17e7.setContent(html_5d26f04f76069d720ed9ece5f0744501);
            
        

        marker_c91a8b42bd494d09fe52e3fb1bc5348f.bindPopup(popup_1dc94d46c830e4d915c274dbeaae17e7)
        ;

        
    
    
            marker_c91a8b42bd494d09fe52e3fb1bc5348f.bindTooltip(
                `<div>
                     Delta LLC
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
                marker_c91a8b42bd494d09fe52e3fb1bc5348f.setIcon(icon_3885a2507498a4f582b926c27618952d);
            
    
            tile_layer_e56b41a61e78b95745ea5b38260a75a7.addTo(map_caa25e94b15caed6f2e9ef0fda8bfd95);
        
    
                marker_f77a399adb199950a6e6d1c46bb76a9e.setIcon(icon_fa0c582e1072f29272e6193617a177a7);
            
    
                marker_ddfa9c0aa3a35ce79cd4329cddd6c429.setIcon(icon_ab9c52991fbb2e218464ad2fd3c80020);
            
    
                marker_06a2d922142efe66128687de379adf34.setIcon(icon_f30a063fb26a26591372b01f5c3500fd);
            
    
                marker_c91a8b42bd494d09fe52e3fb1bc5348f.setIcon(icon_3885a2507498a4f582b926c27618952d);
            
</script>
</html>

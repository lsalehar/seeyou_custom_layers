# SeeYou Custom Layers

Did you know that you can add a custom layer to your SeeYou Cloud map? It's easy:

1. Create a custom [mapbox style](https://docs.mapbox.com/mapbox-gl-js/style-spec/) that contains "sources" and "layers keys. In the sources layer you can list your GeoJSON or other sources. Use layers array to style your data. You can use my [Ohlstadt Noise Areas](https://github.com/lsalehar/seeyou_custom_layers/blob/main/noise_areas_ohlstadt.json) layer as a template. I style my layers using [Maputnik](https://maputnik.github.io/)
2. Host your layer somewhere online. You can use github or dropbox, whatever hosting service that allows internet access to your file without authentication.
3. Add the web addres of your file to the "Custom layer" in SeeYou Layers. If you're hosting the file on github.com make sure you use the "raw" http address you can get it by pressing the "Raw" button when viewing a file. For Ohlstadt Noise areas this address is: https://raw.githubusercontent.com/lsalehar/seeyou_custom_layers/main/noise_areas_ohlstadt.json

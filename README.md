# MapBox
Objetivo: conseguir fazer coisas [destas!](https://www.mapbox.com/industries/telecomm) 



* map.html: mapa MapBox com representação de pontos (marcadores). [[1]](https://docs.mapbox.com/mapbox-gl-js/example/simple-map/)
* map-geojson.html: mapa MapBox com pontos especificados em formato GeoJSON [[2]](https://docs.mapbox.com/help/tutorials/custom-markers-gl-js/)
* map-com-geometrias.html: mapa MapBox com representação de ponto e polígono [[3]](https://docs.mapbox.com/mapbox-gl-js/example/multiple-geometries/)
* map-earthquake.html: primeira experiencia de heatmap. no entanto nao faz o que pretendo. queria que fizesse interpolação de cores intermedias, para conjunto de pontos

existe diferentes estilos de mapas: 
* satelite (satellite-v9)
* light-v10
* dark-v10

## Raster tiles
* info, https://docs.mapbox.com/api/maps/raster-tiles/
* exemplos: 
   * https://docs.mapbox.com/mapbox-gl-js/example/image-on-a-map/
   * https://gis.stackexchange.com/questions/332289/mapbox-gl-js-setting-bounds-of-raster-tile-layer
   * https://blog.mapbox.com/visualizing-radar-data-with-vector-tiles-117bc5ee9a5a
   * http://bl.ocks.org/danswick/a4de5c170c04fdd38bb4
   * https://blog.maxar.com/leading-the-industry/2020/maxar-and-mapbox-release-interactive-swir-imagery-map-of-california-wildfires
* tileset, https://docs.mapbox.com/studio-manual/reference/tilesets/
* geospatial data, https://docs.mapbox.com/studio-manual/guides/geospatial-data/


### Heatmap
* heatmap, https://docs.mapbox.com/help/tutorials/make-a-heatmap-with-mapbox-gl-js/
* input: conjunto de pontos georeferenciados com valores, sendo criado um heatmap entre estes através de interpolação dos valores intermedios quando se faz zoom
* descrição do package: https://docs.mapbox.com/ios/maps/api/6.3.0/Classes/MGLHeatmapStyleLayer.html 
* exemplo que usa pontos do heatmap guardados num [GeoJSON](https://docs.mapbox.com/mapbox-gl-js/assets/earthquakes.geojson) https://docs.mapbox.com/mapbox-gl-js/example/heatmap-layer/
* exemplo em lisboa: map-earthquake.html

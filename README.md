# MapBox
Objetivo: conseguir fazer [isto](https://www.mapbox.com/industries/telecomm) 



* map.html: mapa MapBox com representação de pontos (marcadores). [[1]](https://docs.mapbox.com/mapbox-gl-js/example/simple-map/)
* map-geojson.html: mapa MapBox com pontos especificados em formato GeoJSON [[2]](https://docs.mapbox.com/help/tutorials/custom-markers-gl-js/)
* map-com-geometrias.html: mapa MapBox com representação de ponto e polígono [[3]](https://docs.mapbox.com/mapbox-gl-js/example/multiple-geometries/)
* map-earthquake.html: primeira experiencia de heatmap. no entanto nao faz o que pretendo. queria que fizesse interpolação de cores intermedias, para conjunto de pontos


**por estudar: criação de heatmaps**:
* tutorial a fazer https://docs.mapbox.com/help/tutorials/make-a-heatmap-with-mapbox-gl-js/
* input: conjunto de pontos georeferenciados com valores, sendo criado um heatmap entre estes através de interpolação dos valores intermedios quando se faz zoom
* descrição do package: https://docs.mapbox.com/ios/maps/api/6.3.0/Classes/MGLHeatmapStyleLayer.html 
* exemplo que usa pontos do heatmap guardados num [GeoJSON](https://docs.mapbox.com/mapbox-gl-js/assets/earthquakes.geojson) https://docs.mapbox.com/mapbox-gl-js/example/heatmap-layer/
* exemplo em lisboa: map-earthquake.html

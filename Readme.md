# Trail Base Map

In this lab we explored Mapbox and Geoserver. I chose a base map color scheme that reflected an outdoor theme. This can be seen in the shades of green and darker blues. I also removed the halo effect from the text on the map features to give the map a more bended look. I also removed map features were not relevant to my base map needs such as land cover types. Once I found a suitable look, I link the base map to leaflet. To see the base map <a href="https://clarype.github.io/TrailBaseMap/">Click here</a>.

<img src="https://github.com/clarype/TrailBaseMap/blob/master/images/org.PNG" alt="Oregon">

wms url image of Oregon

**http://localhost:8080/geoserver/sf/wms?service=WMS&version=1.1.0&request=GetMap&layers=sf:ore_counties&styles=&bbox=-124.56670504390223,41.991794810535794,-116.46326242572455,46.23731681568611&width=768&height=402&srs=EPSG:4326&format=image%2Fpng**

wms url geojson 

**http://localhost:8080/geoserver/sf/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=sf:ore_counties&maxFeatures=50&outputFormat=application%2Fjson**

<a href="https://github.com/clarype/TrailBaseMap/blob/master/assets/ore_counties.geojson.txt">Click here</a> for the link to the geojson file.



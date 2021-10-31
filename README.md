
# Wake County NC Development Area
A color coded map of Wake County designating forest (🟢), agriculture (🟡), water (🔵), developed (🟠), and highly developed (🔴). 

![Wake County](https://user-images.githubusercontent.com/21320677/119030515-fbb32300-b977-11eb-8c5c-f0692e2ad326.png)


## Purpose

To identify exact areas of development within Wake County and to understand urban sprawl.

## Method

Utilized EPSG 2264 as the projection, then raster clipped between the raster file and wake_county.shp file to create a clipped wake raster county. 
Overlayed the clipped raster with symbology to color code areas inside the map with the help of an excel spreadsheet containing grid values. Raster calculated to provide grid values to raster cells. 

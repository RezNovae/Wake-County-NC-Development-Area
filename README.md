
# Wake County NC Development Area
A color coded map of Wake County designating forest (🟢), agriculture (🟡), water (🔵), developed (🟠), and highly developed (🔴). 

![Wake County](https://user-images.githubusercontent.com/21320677/119030515-fbb32300-b977-11eb-8c5c-f0692e2ad326.png)


## Purpose

To identify exact areas of development within Wake County and to understand urban sprawl.

## Method

Utilized NAT83 projection or EPSG 2264, then raster clipped between the projection and wake_county.shp file to create the exact area of wake county. 
Overlayed the clipped projection with symbology to color code areas inside the map with the help of an excel spreadsheet containing grid values. Gave numeric values (1-5) to each designation to help assign grid values from the spreadsheet to each designation. 

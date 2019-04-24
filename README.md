## Visualizing a Forest Stand Using a Point Cloud and Terrain Modeling

Bryan Begay, Thomas Braun, Katie Nicolato | GEOG 572 Geovisual Analytics, Spring 2019

Final Project Proposal | April 23, 2019

### Motives 

Our primary goal is to visualize a forested lidar point cloud overlaid on a terrain template. Our secondary goal is to create a more accurate platform for forest viewshed analysis through this visualization. Point cloud visualization supported by a terrain map allows the viewer to conceptualize aesthetics and elevations for landscapes of varied relief. Viewshed is a geographic area visible from a certain location. Forest managers apply viewshed analysis to forest landscapes to determine silvicultural treatments that will maintain aesthetically pleasing forested views. Our end product will be a method for 3D forest stand visualization accompanied by vector sightline quantification.

### Description 

The project will use a point cloud derived from lidar to develop a model that incorporates terrain to visualize a forested stand in Potree. The project will also include creating a template in 
Potree that will accept tools for stand level analysis. This may include the ability to perform viewshed analysis with the surrounding terrain.  

### Data 

We will use forested lidar datasets derived from the Oregon Lidar Consortium DOGAMI Lidar Viewer:
https://gis.dogami.oregon.gov/maps/lidarviewer/

We will use a basemap created with a Potree template. If possible, we will integrate a 3D terrain basemap through Cesium. The Potree Cesium Sorvilier is an example of 2D basemap integration with a 3D point cloud:  http://www.potree.org/potree/examples/cesium_sorvilier.html

### Interface Design 

We will use the Potree Viewer as a model for our interface design. This Elevation Profile is an example of what our final product will look like: http://www.potree.org/potree/examples/elevation_profile.html
Similar to the vector red line indicating an elevation transect, we will have a vector “wedge” indicating viewshed area. If the user places a point outside of the forest point cloud, the vector wedge will appear indicating visible landscape to a viewer standing at that point. A similar concept of a vector dataset overlaid onto a terrain model is shown in this Potree Shapefiles example: 
http://www.potree.org/potree/examples/shapefiles.html


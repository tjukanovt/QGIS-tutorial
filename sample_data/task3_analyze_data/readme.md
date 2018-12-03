# Task description
In this task you can explore metro and tram stations in Amsterdam and perform basic GIS operations (buffers, intersects) with them.  

You should add all the vector layers to your project. First you should merge the bars and pubs in to a single vector layer (Merge Vector Layers) . Then you should explore the spatial relationship between this newly created layer and the public transport stops. To create a correct buffer for the stops, you need to reproject them. You can do this with Processing toolbox Reprojection tool. After your layer is reprojected, you can use the Buffer tool to create a 200 meter buffer around the stops. After this you should select the OpenStreetMap bars and pubs that are within this distance from the stops and analyze the data in the way you see most informative (e.g. Join attributes by location and create a thematic map). You can use the tram and metro lines to visualize your data.  

OSM bars and pubs collected using QuickOSM. © OpenStreetMap contributors. 

Public transport data was downloaded [here](https://maps.amsterdam.nl/open_geodata/).

You can find a detailed explanation of the process of buffers and spatial relationships [here](https://www.qgistutorials.com/en/docs/performing_spatial_queries.html).

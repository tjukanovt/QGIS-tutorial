# Task description
Ability to join data from different sources is one of the basic operations in GIS. You can do table joins and spatial joins. In this task you can join population data with city districts. The GEBIEDEN22_EXWATER.json GeoJSON file contains 22 city ditrict boundaries and the xlsx file contains number of foreign nationalities living in those districts. The file has been cleaned for easier joining to a ccsv file.  

You should add the ditsricts to QGIS and join it with the cleaned csv file. Then you should normalize a population field of your choice with the total population of the districts using Field Calculator to get the exact percentage share of that nationality in each districts. From these results you should create a coropleth map.

Data originated from [here](https://maps.amsterdam.nl/open_geodata/).  

A lengthy and detailed step-by-step guide on how to do a table join can be found [here](https://www.qgistutorials.com/en/docs/performing_table_joins.html)

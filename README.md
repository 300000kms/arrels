# arrels
## Make an atlas, print it, draw, scan and analize. 
## The power of the paper for the collaborative surveys

###what is it ?
This tool has been developed by 30000Km/s to help Arrels foundation to make the annual survey to count homeless people in Barcelona. 
The objective is provide to an amount of 900 volunteers a cartography of the city organized and coordinated to be distributed in different teams
Once the data is on the paper, it can be scanned and digitized


###how is it?

This tool is very experimental.
Is made by three main blocks of code:

- 1  city divider: 
  - 1.1 divide the city in differents parts
  - 1.2 determine how many meters of paths there are
   - 1.3 determine how big is each area
   - 1.4 determine how subdivide each zone for a comfortable exploration
   
- 2 atlas builder (for Qgis):
 - 2.1 map maker: you can use your custom shapefiles, the cadaster files from spain or any web tile service
 - 2.2 form maker: you can configure the form that will be printed with each sheet of map 
  
- 3 scan reader:
 - 3.1 digitize the maps
 - 3.2 digitize the forms

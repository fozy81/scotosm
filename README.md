scotosm
=======

Scotland OSM mining for bicycle data:

Rcode, this code runs in R. Brings back a table of stats and creates maps showing NCN cycle routes in Scotland. 
You will need to point it to  boundary files saved locally and install libraries into R. The list of libraries is at the start of the script. This was tested on Ubuntu LTS 12.04

The R script also requires osmosis to be installed on your system: http://wiki.openstreetmap.org/wiki/Osmosis

Boundaries folder contains simplified polyline MSP boundaries used by R script to 'cookie cut' areas to create stats for each constituency. 

That's about it for the moment...




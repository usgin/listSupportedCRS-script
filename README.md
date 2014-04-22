listSupportedCRS-script
=======================

Python script to edit JSON properties for ArcServer web services for ArcMap10.1 and up, specifically the listSupportedCRS property to indicate mulitple supported projections.

To run:
-          Unzip the file
-          Open in a python environment (I use IDLE – I’m not a python expert by any means, but this one that I know)
-          You can open and edit the script if you’d like, or can just run
-          Run the script
-          It will ask you to:
o   Enter server name (server URL): 
o   Enter server port (usually 6080): 
o   Enter folder in your service directory to edit services (assumes the root is '/arcgis/admin/services/'):
o   Enter admin user name: 
o   Enter password:
-          And it runs – it will edit all the services in that directory. I have an aasggeothermal directory, so just ran this on all the services in that one.


 Script and text provided by Doug Curl, Kentucky Geological Survey, 2014.
listSupportedCRS-script
=======================

Python script to edit JSON properties for ArcServer web services for ArcMap10.1 and up, specifically the listSupportedCRS property to indicate mulitple supported projections.

To run:
-          Unzip the file
-          Open in a python environment (i.e., IDLE)
-          You can open and edit the script if you’d like, or can just run
-          Run the script
-          It will ask you to:
          -          Enter server name (server URL): 
          -          Enter server port (usually 6080): 
          -          Enter folder in your service directory to edit services (assumes the root is '/arcgis/admin/services/'):
          -          Enter admin user name: 
          -          Enter password:

This will edit all the services in the specified directory.


 Script and text provided by Doug Curl, Kentucky Geological Survey, 2014.